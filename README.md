# challenge-01
Customize nginx image with selfsigned certificate and nginx image

### About this challenge

* Make custome nginx docker image with docker file 
* Insert custome index.html in nginx image
* Kubernetes Deployment manifest with replica 2 and service, ingress, selfsined certificate

### Before run 

* You need deploy nginx ingress in your cluster
* You need deploy certmanager in your cluster

#### 1) build docker file in your worker node

```bash
docker build -t saeed-nginx .
```

#### 2) deploy manifest in your kubernetes cluster

```bash
kubectl create -f deployment.yaml
```
