Projeto desenvolvido a partir de um curso no YouTube da Michelli Brito, onde foi construído o user-microservice e email-microservice,
foi implementado a comunicação assíncrona entre eles utilizando mensageria com rabbitMQ e envio de emails com smtp do gmail.

/////////////////////////////////////////////////////////////

Base do application.properties para o microsservico de user:

server.port=

spring.datasource.url=

spring.datasource.username=

spring.datasource.password=

spring.jpa.hibernate.ddl-auto=

spring.rabbitmq.addresses=

broker.queue.email.name=


/////////////////////////////////////////////////////////////////


Base do application.properties para o microsservico de email:

server.port=

spring.datasource.url=

spring.datasource.username=

spring.datasource.password=

spring.jpa.hibernate.ddl-auto=

spring.rabbitmq.addresses=

broker.queue.email.name=

spring.mail.host=

spring.mail.port=

spring.mail.username=

spring.mail.password=

spring.mail.properties.mail.smtp.auth=

spring.mail.properties.mail.smtp.starttls.enable
