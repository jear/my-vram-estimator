```
npm install
npm run dev
npm run build

# Copy Dockerfile in ./out
docker build ...
docker push

# Deploy in k8s
kubectl apply -f ./deploy-dev/01_namespace.yaml
...
```
