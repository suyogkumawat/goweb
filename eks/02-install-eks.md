# Install EKS

Please follow the prerequisites doc before this.

## Install a EKS cluster with EKSCTL, Note it will launch 2 worker nodes with m5.large instance type by default

```
eksctl create cluster --name project-eks-cluster --region ap-south-1 --node-type t2.medium
```

## Delete the cluster

```
eksctl delete cluster --name project-eks-cluster --region ap-south-1
```
