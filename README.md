# Custom Cluster Instance Classes For TAP 1.5+
This repo contains examples for custom cluster instance classes that are based on crossplane compositions for TAP usage.

These examples enable additional services to be used for dynamic service provisioning beyond the OOTB bitnami ones supplied in TAP 1.5.

# Current examples
1. [MongoDB using the Bitnami Helm chart](./helm-based/mongodb/)
2. [RabbitMQ using the Tanzu RabbitMQ or OSS RabbitMQ Operator](./tanzu-operators/rabbitmq/)
3. [Single Node MSSQL Using plain K8s YAML](./kubernetes-native/mssql)


# WIP
1. Tanzu MySQL
2. Tanzu PostgreSQL
3. Zalando PostgreSQL
4. Bitnami based Kafka
