kubectl apply -f artifacts/examples/crd.yaml
kubectl apply -f artifacts/examples/crd-status-subresource.yaml
kubectl apply -f artifacts/examples/example-foo.yaml
kubectl apply -f artifacts/examples/nginx.yaml


kubectl get pods -o wide
kubectl get svc -o wide
iptables -t nat -S | grep nginx
