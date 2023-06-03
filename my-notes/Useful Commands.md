## Kubectl
kubectl config view
kubectl get nodes



## Clusters

### K3d
k3d cluster list

## Pods
kubectl explain pods --recursive
kubectl explain pod.spec.restartPolicy
kubectl get pods
kubectl get pods -o yaml
kubectl describe pods <pod>

running command in pod
kubectl exec <pod> -- <linux command>


## Services
Show Service 
kubectl get svc 

## Ingresses

## Deployments
kubectl get deploy <deployment-name>
kubectl describe deploy <deployment-name>


## ReplicaSets
kubectl get rs