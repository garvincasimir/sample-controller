kubectl apply -f artifacts/examples/crd.yaml
kubectl apply -f artifacts/examples/crd-status-subresource.yaml
kubectl apply -f artifacts/examples/example-foo.yaml
kubectl apply -f artifacts/examples/nginx.yaml

kubectl get nodes -o wide
kubectl get pods -o wide
kubectl get svc -o wide
iptables -t nat -S | grep nginx


https://learn.microsoft.com/en-us/azure/aks/concepts-clusters-workloads
https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.22/#deployment-v1-apps
