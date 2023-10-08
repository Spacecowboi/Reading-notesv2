# AWS Cloud Servers

### AWS EC2

1. What is an EC2 instance?

* " A web service that provides resizeable compute capacity in the cloud. It is designed to make web-scale computing easier for developers.

2. Name 2 use cases for EC2.

* Web Application Hosting
* BIG data processing

3. Provide 1 reason to use ECS isntead of a service such as Heroku, Digital Ocean, or Render.com.

* Better flexibility. EC2 offers much higher and broader "scaling" than any of the other listed services.

### EC2 for Humans

1. Where can we find EC2 on the AWS Console?

* In the "compute" category on the dashboard

2. Explain the general difference between T2 Micro and XL

* It depends on what you need to use each of them for because they offer different things for different workloads. T2 for small-scale projects and XL for larger ones are the biggest and most notable differences.

3. Explain a "Compute Cycle" to a non-technical friend.

* A "compute cycle" is like a tiny thing that happens when the computer is trying to process information. Think of it as a micro-process. You don't "think" when you decide you are going to move your hand, you just do it. Under the hood though, your brain is sending numerous different signals to your hand in order to make that happen. A "compute cycle" is like those underlying messages.

### Elastic Beanstalk

1. What is Elastic Beanstalk?

* "An easy-to-use service that manages, deploys, and scales web apps and services for you."

2. Describe the relationship between EC2 and Elastic Beanstalk.

* Elastic Beanstalk utilizes EC2. It (beanstalk) uses the instances created from EC2 in order to host and run your web apps. When you deploy using beanstalk, it atuomatically creates and manages the required isntances made by EC2.

3. Name some benefits of using Elastic Beanstalk.

* Easy Deployment
* Automatic and Large Scaling
* Cost effective