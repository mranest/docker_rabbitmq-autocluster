# RabbitMQ image with autocluster plugin

The standard upstream RabbitMQ image with the [RabbitMQ peer discovery and cluster formation plugin](https://github.com/rabbitmq/rabbitmq-autocluster) included. Based on the work of [kubernetes-rabbitmq-autocluster](https://github.com/lcantelli/kubernetes-rabbitmq-autocluster).

# TODO

- Treat erlang cookie as a secret in the sample k8s configuration files