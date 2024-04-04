```
# Test/Dev locally
npm install
npm run dev
npm run build

# Build Dockerfile with ./out content
docker build -t harbor.datasvc01.lysdemolab.fr/jear/vram-calculation:v0.3-dev .
docker push harbor.datasvc01.lysdemolab.fr/jear/vram-calculation:v0.3-dev


# Deploy in k8s
kubectl apply -f ./deploy-dev/01_namespace.yaml
...
```
# Credits
https://github.com/furiousteabag/vram-calculator/tree/main
