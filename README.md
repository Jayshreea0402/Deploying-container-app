# Deploying-container-app
Deploying a container app to Kubernetes pods.
Create a deploying using the deployment.yaml file 
    kubectl create -f deployment.yaml
Verify the deployment
    kubectl get pods -o wide
Copy the internal IP
Execute the pod
    kubectl exec -it nginx -c test-nginx -- /bin/bash
    curl internal-IP:80
    
