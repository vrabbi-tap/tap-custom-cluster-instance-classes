# Tanzu MySQL Based Instances
## Install Operator
Follow the [official documentation](https://docs.vmware.com/en/VMware-SQL-with-MySQL-for-Kubernetes/1.7/vmware-mysql-k8s/install-operator.html)

## Creating TAP configuration
```bash
kubectl apply -f ./
```  

## Creating a claim
```bash
tanzu services class-claim create mysql-example --class mysql
```
