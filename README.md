## a. What is amqp?

AMQP (Advanced Message Queuing Protocol) is an open standard messaging protocol that enables asynchronous communication between applications via message queues. It is commonly used with message brokers like RabbitMQ to support reliable message delivery, persistence, routing, and decoupled communication between systems.

## b. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?

- The first guest is the username used to authenticate the connection to the message broker.

- The second guest is the password for that user.

- localhost refers to the host address where the message broker (e.g., RabbitMQ) is running. localhost means it's running on the same machine.

- 5672 is the default port used by AMQP to accept non-SSL connections.
