# K8s Real time Practice Code. 
# Important command in K8s.

kubectl get pod = to see all pod (Resource)
kubectl explain pod = To validate option/configuration use in pod (Resource) 
kubectl describe pod pod-name = to chcek the detaile information and event of that resource.
kubectl logs = shows application or container logs.
kubectl get po -o wide = to check attach ip with pod and running on which no 
kubectl api-resources | find -i po = to check short name of that command and also craete in ns.

kubectl scale rs rs_name --replicas=2 = to scale the number of the rsporces.



