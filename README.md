# rabbitMQ configuration for .net 7 
## install rabbitMQ on docker 
```
docker pull rabbitmq 
# web port 8080 and rabbitmq port 9990 
docker run --restart unless-stopped -d --name rabbitMQ -p 9990:5672  -p 8080:15672 --hostname rabbitMQ -e RABBITMQ_DEFAULT_USER=admin -e RABBITMQ_DEFAULT_PASS=yourPassword rabbitmq:3-management
```
