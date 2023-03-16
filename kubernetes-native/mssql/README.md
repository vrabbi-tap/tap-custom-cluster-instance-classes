# Installation
To install you need to first install the Crossplane SQL provider running the following:
```bash
kubectl apply -f https://raw.githubusercontent.com/vfarcic/devops-toolkit-crossplane/master/crossplane-config/provider-sql.yaml
```  
Now you can simply apply the files in this folder:
```bash
kubectl apply -f ./
```
And now you can create a claim for example:
```bash
tanzu services class-claim create example-mssql --class sqlserver-unmanaged --parameter storageGB=20
```
