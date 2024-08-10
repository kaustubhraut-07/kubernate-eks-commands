# Setuping the EKS Cluster with the help of command 

## Before executing this command make sure you have installed all the necessary things like kubectl, eksctl, awscli, helm.

## Install EKS

### Install using Fargate

```  
eksctl create cluster --name <cluster-name> --region <region-code> --fargate
``` 

### Delete the cluster
``` 
eksctl delete cluster --name <cluster-name> --region <region-code>
```

