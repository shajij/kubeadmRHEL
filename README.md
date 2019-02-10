# kubeadmRHEL
Setting up and Installing a Kubernetes Cluster with Kubeadm

Ref: 

1. Needs to be run with Sudo
2. if you need the master node to take pods then run this
kubectl taint nodes --all node-role.kubernetes.io/master-
