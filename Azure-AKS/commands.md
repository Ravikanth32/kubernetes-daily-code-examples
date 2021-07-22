Azure Login:

az Login

Add subscription:

az account set --subscription <SUB-ID>



Add kubernets cluster to my local kubeconfig:

az aks get-credentials --resource-group <RG-NAME> --name <CLUSTER-NAME>


Go to kube-deployment Folder:

cd kube-deployment

Apply deployment.yml( This conatins deployment and service)


kubectl apply -f deployment.yml


kubectl get pods

kubectl get service --watch

kubect get service service-vote-front 

