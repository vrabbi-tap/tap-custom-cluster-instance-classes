# RabbitMQ Operator based cluster
## Install the operator
#### Option 1 - OSS Operator
```bash
kubectl apply -f https://github.com/rabbitmq/cluster-operator/releases/download/v1.14.0/cluster-operator.yml
```  
#### Option 2 - Tanzu RabbitMQ Operator
Follow the [official documentation](https://docs.vmware.com/en/VMware-RabbitMQ-for-Kubernetes/1.4/rmq/GUID-installation.html)
  
## Creating TAP configuration
```bash
kubectl apply -f ./
```  

## Create claim
```bash
tanzu services class-claim create rabbit-cluster --class rabbitmq
```
