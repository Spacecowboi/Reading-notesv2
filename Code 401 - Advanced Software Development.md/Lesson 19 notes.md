## AWS SQS vs SNS

1. What is the difference between SQS and SNS?

* SQS is a distributed *queuing* service. SNS is a distributed *publish-subscribe* service.

2. What are some use cases for both SNS and SQS?

* Sns if you want to send notifications via email, SMS. SQS for complex workflow where a bunch of different things need to happen in a sequence.2

## AWS SNS && SQS

1. Describe how to use SQS and SNS in a "fanout" pattern.

* It's essentailly broadcasting messages from a single source to multiple sbuscribers.

2. Explain how "push notifications" work, using SNS.

* Create an SNS Topic > Configure subscriptions > Register Devices and Endpoints > Subscribe Devices and Endpoints and finally > push notifications

## SQS && SNS Basics

1. How might a large scale, distributed application make use of a Queue system like SQS?

* It would improve the "structure" of it, making it more effecient at scale, and give it versatility.