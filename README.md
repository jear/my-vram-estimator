# my-vram-estimator
```
npm install
npm run dev
npm run build

cp Dockerfile ./out
cd ./out
docker build -t harbor.datasvc01.lysdemolab.fr/jear/vram-calculation:v0.2 .
docker push harbor.datasvc01.lysdemolab.fr/jear/vram-calculation:v0.2

cd deploy-dev
kubectl apply -f 01_namespace.yaml
kubectl apply -f 03_deployment.yaml
kubectl apply -f 04_service.yaml
kubectl apply -f 05_ingressroute-websecure-gpu03-nip.yaml
```
# Credits
https://github.com/furiousteabag/vram-calculator/
