# Nginx-with-K8s

This project that I have done was with docker and Minicube cluster.

Created a Dokcer Image for nginx and added the .html file content to the docker.
Build the file and pushed the image to my dockerhub.
Created a .yaml file were the deployment and service was in the same file.
Used the image that I have created. 
Added the NodePort the external Connection using the minikube IP.
I have faced small challanges while the creation, all the service and the depolyment running but the site was not loading.
I have errors that I have corrected was, First I used the LoadBalancer type, then changed to the node por. The Name of the app in deployment and 
service should be the same.

