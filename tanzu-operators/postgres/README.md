# Tanzu PostgreSQL Based Instances
## Install the operator
Follow the [official documentation](https://docs.vmware.com/en/VMware-SQL-with-Postgres-for-Kubernetes/2.0/vmware-postgres-k8s/GUID-install-operator.html)
  
## Creating TAP configuration
```bash
kubectl apply -f ./
```  

## Create claim
```bash
tanzu services class-claim create psql-example --class postgresql
```
