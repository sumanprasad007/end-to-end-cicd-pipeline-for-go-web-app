# Install EKS

Please follow the prerequisites doc before this.

## Install a EKS cluster with EKSCTL

```
eksctl create cluster --name k8s-cluster --region us-east-1 
```

## Delete the cluster

```
eksctl delete cluster --name k8s-cluster --region us-east-1
```