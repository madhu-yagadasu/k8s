# k8s
K8s Practice repo with killerkoda practice files

# Imperative Commands

kubectl run nginx --image=nginx
kubectl run nginx --image=nginx --dry-run=client -o yaml
kubectl delete po nginx --force
kubectl scale deploy --replicas=3
hello