
kubectl create deployment --image=nginx nginx --dry-run=client -o yaml > nginx-deployment.yaml

