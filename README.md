# simple-django-nodeport-example
deploying django app using nodeport service 
commands used to deploy app using nodeport in minikube cluster:

build docker image using below command:
docker build -t himani708/newimage:v2 .

Run deployment.yml file:
kubectl apply -f deployment.yml

Run service using svc.yml:
kubectl apply -f svc.yml

in browser type below to see application running
http://<workernode/minikube ip><nodeport>

<img width="737" height="304" alt="image" src="https://github.com/user-attachments/assets/4a324461-9b4b-4ea3-ab00-b336e07afce7" />

