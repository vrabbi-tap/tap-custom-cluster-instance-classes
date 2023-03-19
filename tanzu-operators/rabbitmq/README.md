# RabbitMQ Operator based cluster
## Install the operator
```bash
kubectl apply -f https://github.com/rabbitmq/cluster-operator/releases/download/v1.14.0/cluster-operator.yml
```  

## Create claim
```bash
tanzu services class-claim create rabbit-cluster --class rabbitmq
```
