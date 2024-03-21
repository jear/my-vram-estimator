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
kubectl apply -f 01_
kubectl apply -f 03_
kubectl apply -f 04_
kubectl apply -f 05_
```
