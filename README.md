# RabbitMQ

Studying RabbitMQ with .net core.

## Installing RabbitMQ Server with docker

```docker pull rabbitmq```

```docker run -d --hostname my-rabbit --name some-rabbit -p 8080:15672 -p 5672:5672 rabbitmq:3-management```

### RabbitMQ plugin management

Address: http://0.0.0.0:8080

user: guest

password: guest
