# Events

## AWS SQS vs SNS

* *What is the difference betweeen SQS and SNS?*

  * SNS automatically sends messages out to those that are subscribed, SQS is a mailbox, that you have to check and see if you have messages.
* *What are some use cases for both SNS and SQS?*

  * SNS you can use if you need to send to multiple subscribers, sqs you only need one subscriber.
## AWS SNS and SQS

* *Describe how to use SQS and SNS in a “fanout” pattern.*

  * In a fanout pattern, create an SNS topic and multiple SQS queues. Subscribe each SQS queue to the SNS topic, and messages published to the topic are delivered to all subscribed queues.
* *Explain how “push notifications” work, using SNS.*

  * SNS push notifications are messages sent from a server to client devices without a client request. With SNS, create a topic, configure platform-specific credentials, and register client devices to send notifications.
## SQS and SNS Basics

* *How might a large scale, distributed application make use of a Queue system like SQS?*

  * SQS can be used in large-scale applications for decoupling components, load leveling, buffering, retry/error handling, and scalability. It allows components to evolve independently and improves performance and reliability.
