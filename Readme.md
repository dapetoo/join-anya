# JoinAnya DevOps Aptitude Test

## Full Name

Peter Dada

## Email Address

dapetoo@gmail.com

## What is a project you have worked on that was a major accomplishment for you?

A mobile chatbot app using IBM Watson SDK

## In reference to Q1, What was the biggest challenge you encountered? How did you deal with it? *

Implementing the app on different platform and making sure the user experience is the same, I was able to handle it by using logic operators to handle the platform and the experience was unique when it was demoed on the project defense day

## What was the most difficult engineering project you've worked on? *

Deploying a logistics app to Amazon Web Services using Docker platform on Elastic Beanstalk, CodeBuild to handle the building of artifacts and test cases, CodePipeline to enable continuous integration and continuous deployment/delivery

## Rebase or merge strategy? *

Both git rebase and git merge merge changes from one branch into another. Where they diverge is in how they go about it. Git rebase merges a feature branch into the master branch. Git merge creates a new commit while keeping the history.

## What's O (n log n)? *

Linearithmic time (O(n log n)) approach is a combination of linear time (O(n)) and logarithmic time (O(log n)). Efficient sorting algorithms like merge sort, quicksort, and others.

## Compare and contrast REST APIs and GraphQL endpoints. *

GraphQL is a server-side application layer technology used for query execution with existing data, whereas REST is a software architectural style that defines a set of constraints for creating Web services.
GraphQL can be organized using a schema, whereas REST can be organized using endpoints.
The development speed of GraphQL is quick, whereas the development speed of REST is slow.
GraphQL mutations should have a string message format, whereas REST mutations can have any message format.
GraphQL uses metadata to validate queries, whereas REST does not have machine-readable metadata that can be cached.

## Where would you like to use a solution like RabbitMQ? *

RabbitMQ is a lightweight messaging protocol that is simple to deploy both on-premises and in the cloud. It supports a variety of messaging protocols. Software applications can connect and scale with the help of messaging. Applications can connect to each other, or to user devices and data, as part of a bigger application. Messaging is asynchronous, separating sending and receiving data to decouple programs.

## Kubernetes

## What are some ,major benefits of using K8S? *

Portability and flexibilty
Scaling services
Decouplin10. g
Multi-cloud capability
Open source

## What is a sidecar? When would you use one? *

Sidecar pattern is used to reduce the internal complexity of a Microservice, toused to separate cross-cutting procedures. For example, imagine we wish to run numerous modules for each Microservice, such as logging, messaging, and monitoring. However, because these actions are so identical, replicating the code for handling them in each Microservice isn't worth it.
In such cases, the Sidecar pattern can be used to solve the problem. The Sidecar pattern, as its name implies, allows us to run components such as logging and monitoring separately while remaining connected to the principal service.

## What was a major problem you encountered while maintaining a production cluster? *

## What is an Operator? Why might you need one? *

Operators are Kubernetes software extensions that use custom resources to manage applications and their components. Kubernetes principles, particularly the control loop, are followed by operators. Kubernetes operators make these processes scalable, repeatable, and standardized by removing difficult manual application management tasks.

## When would you use Minikube? *

Minik

Deployments

## What are some deployment strategies we could use to minimize downtime? *

Blue Green Deployment strategy
Monitoring and Alerting
Implementing high availabilty

## Why would we use blue/green deployment strategy? What's the downside? *

Blue/green deployment is a continuous deployment strategy that uses two identical production environments, blue and green, to reduce downtime and risk.  The blue environment is active, whereas the green environment is dormant. When a developer wants to release new code of any kind – a new feature release, a new version of an application, etc. – the new version is worked on in the green environment, while the old version is kept in the blue. When the new release is complete, the load balancer redirects all production traffic to the green version, while the blue version is kept as a backup. After the green version has been tested and found to be bug-free, the old blue version is retired, the currently-live version becomes the blue, and a new production environment clone is created to become the new green.

Downside(Resource intensive, Expensive, Database problem)

## How could we release features to a specific subset of our users? *

Canary deployments are recommended for teams that have adopted a continuous delivery process. A new feature is first made available to a small subset of users using this strategy. Depending on traffic volume, the new feature is monitored for several minutes to several hours, or just long enough to collect meaningful data. If the team discovers a problem, the new feature is quickly removed. If no issues are discovered, the feature is made available to all users.

## NETWORKING

## What is RFC 1918? *

RFC 1918, also known as Request for Comment 1918, is an Internet Engineering Task Force (IETF) document that describes methods for assigning private IP addresses on TCP/IP networks. RFC 1918 defines the IPv4 private IP addresses that are usable. Private IP addresses do not need to be registered with a Regional Internet Registry (RIR), making it easier to set up private networks.

RFC 1918 was used to develop the standards that govern how networking equipment assigns IP addresses in a private network. A single public IP address can be used by a private network.

## What is the subnet of a /18? *

The subnet of a /18 is 255.255.192.0 with 16,384 IP addresses

## How would you create a dynamic SSH tunnel? *

ssh -R [REMOTE:]REMOTE_PORT:DESTINATION:DESTINATION_PORT [USER@]SSH_SERVER

## How would you test TLS connections? *

Try to connect to a port
Check TLS certificate using openssl command
Use online tool SSL labs, SSL Checker etc

## OBSERVABILITY

## Explain an ideal observability stact, Its importance and how you would set it up? *

Observability is a method for gaining insights into the entire infrastructure. It's critical for the operations team. Observability entails assembling all fragments from logs and monitoring tools and organizing them in such a way that they provide actionable knowledge of the entire environment, resulting in an insight. It is the combination of multiple items to create a deep understanding of actual health, real issues, and what should be done to improve the environment, as well as root-cause troubleshooting.

Logging
Fluentd
Logstash
Prometheus
Grafana

## Why do we need to think about SLOs and SLAs? *

SLA, or Service Level Agreement, is a contract that a service provider makes to its customers regarding service availability, performance, and so on. SLO, or Service Level Objective, is a target that a service provider wishes to achieve.

## What key things should we alert on with MVP? *

Logs
Error
Usage pattern

## TROUBLESHOOTING SCENARIOS

You are asked by an engineer to help troubleshoot a service that's malfunctioning. They say they are not sure why their service is crashingand why they can't seem to access logs which they'd usually access using docker exec and via the /var/log path in the container. They say they're not sure which of the container processes are failing. What are some of the things you'd want to talk about? *

## What can you already tell from the problem description? *

## What about the separation of concern? *

## Logging outside the container? *

## Fit: Hopefully the candidate asks a question or two, doesn't get judgemental/condescending *
