# DevOps Task 5 - Minikube and Kubernetes Deployment 
 
## Task Summary 
 
### a. Installed Docker and Minikube 
- Docker Desktop installed and running. 
- Minikube installed and started with Docker driver. 
 
### b. Created deployment.yaml 
- Defined a Deployment for an nginx app with 2 replicas. 
- Used labels for app identification. 
 
### c. Created service.yaml 
- Exposed the deployment as a NodePort service on port 8080. 
 
### d. Verified pods and services 
- Used kubectl get pods to check pods status. 
- Used kubectl get svc to check service details. 
 
### e. Scaled deployment 
- Scaled hello-minikube deployment to 3 replicas using: 
``` 
kubectl scale deployment hello-minikube --replicas=3 
``` 
- Verified the new pods are running. 
 
### f. Used kubectl describe and logs 
- Described pods and deployment for detailed info. 
- Checked logs from pods using kubectl logs. 
 
## Kubernetes Objects Used 
 
- Deployment (hello-deployment with nginx container) 
- Service (hello-service NodePort exposing deployment) 
 
## Status Outputs 
 
- Minikube status: Running control plane and nodes. 
- Pods: Running 3 replicas of hello-minikube. 
- Service: NodePort listening on port 8080. 
 
--- 
 
This project demonstrates basic Kubernetes deployment lifecycle including starting Minikube, creating deployments, exposing services, scaling pods, and checking logs. 
