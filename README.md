# Microservices with Spring Boot and Spring Cloud Training Plan
> Jul 07, 2020

## TARGETS

### Spring core & Spring boot 

#### Spring core & Spring boot knowledge

#### Spring Security
- Understanding Spring Security concepts
- Understanding about OAuth2, OpenID
- Learning how to setup, implement, secure APIs using Spring Security with OAuth 2
- Understanding about common vulnerabilities and how to avoid them in the real world

#### Spring Cache
- Understanding Spring Caching
  - Understand Spring Cache Abstraction
  - Understand cache annotations
  - How to define a key for cache entry
- Using Spring Caching with Redis
  - How to config Spring caching to work with Redis.
  - How to apply all caches expired in a specific duration (Say 1 minute)
  - How to apply a specific cache expired in a specific duration (Say 1 minute)
  - How to apply a specific cache or all caches never expired
  - How to reset a specific cache or all caches by a specific time (Say at 5AM everyday)
  
#### Spring Messaging
- Understanding Message, Messaging.
- Understanding Messaging protocols.
- Focus on Spring AMQP, RabbitMQ and why we should use them.
  - 4 Actors of Messaging with RabbitMQ - Exchanges, Queues, Topics and Bindings
- Application Development Basics with Spring AMQP and RabbitMQ.
- Configuring Queues and Exchanges with Spring AMQP and RabbitMQ.
- Configuring Bindings, Topics (also called as Routing Keys).

#### Spring Batch
- Understand the infrastructure to design, develop, and execute a batch application.
- Configure batch jobs work, execute from diverse platforms
- Develop batch jobs with essential read, process, and write features different forms of data
- Learn the techniques you can use to manage transactions, control job flows, and utilize data sharing
- Integrate Spring Batch with other technologies to develop robush batch applications
- Monitor and report the batch job execution updates by accessing live job execution information
- Perform unit integration and functional testing on Spring Batch applications

### Spring Cloud
- Spring Cloud Config
- Spring Cloud Netflix
- Spring Cloud Bus
- Spring Cloud Cloudfoundry
- Spring Cloud Open Service Broker
- Spring Cloud Cluster
- Spring Cloud Consul
- Spring Cloud Security
- Spring Cloud Sleuth
- Spring Cloud Data Flow
- Spring Cloud Stream
- Spring Cloud Stream App Starters
- Spring Cloud Task
- Spring Cloud Task App Starters
- Spring Cloud Zookeeper
- Spring Cloud Connectors
- Spring Cloud Starters
- Spring Cloud CLI
- Spring Cloud Contract
- Spring Cloud Gateway
- Spring Cloud OpenFeign
- Spring Cloud Pipelines
- Spring Cloud Function

### Microservices Architecture 
> Reference: https://www.edureka.co/microservices-architecture-training

#### Evolution of Microservices
**Learning Objectives:** In this Module, you will learn how Microservices have evolved over time and how different is Microservices from SOA. In addition, you will get to know about different architectures and where does Microservices architecture fit. 

**Topics:**
- Monolithic Architecture
- Distributed Architecture
- Service oriented Architecture
- Microservice and API Ecosystem
- Microservices in nutshell
- Point of considerations
- SOA vs. Microservice
- Microservice & API

##### Microservices Architecture
**Topics:**
- REST Architecture principles
- Microservice Characteristics
- Inter-Process Communications
- Microservice Transaction Management

##### Microservices - Design
**Learning Objectives:** This Module gives you an insight into Domain Driven Design, the approach called Big Ball of Mud, the approaches and their strategies that can be used while moving from Monolithic to Microservices. 

**Topics:**
- Domain Driven Design
- Big Mud Ball to Sweet Gems
- Untangling the Ball of MUD
- Kill the MUD Ball growth
- Repackaging/Refactoring
- Decouple the User interface and Backend Business Logic
- MUD Ball to Services
- Microservice Design Patterns
- Microservice Architecture Decisions

##### Microservices - Security
**Topics:**
- Why is Security important? 
- Microservice Security Principles
- Microservice Security techniques
- Access Tokens
- Oauth 2.0
- How to secure a Microservice using OAuth 2.0

##### Microservices - Testing
**Learning Objectives:** Learn the different testing strategies that can be implemented in Microservices, how Spring Boot features help in testing Microservices, and the various testing tools that are available to be used.

**Topics:**
- Testing scenarios and strategy
- Test at Different Levels
- Testing Best Practice for Microservices

### Practice: 
Build an e-commerce system: Admin Service. Seller Service, Buyer Service
- Reading properties in various ways
- Implementing config server
- Setting up Discovery Server
- Setting up Discovery Client
- Overview of Actuator Endpoints
- API Gateway and Dynamic Routing
- IDeclarative Rest Client
- Hystrix Fault Tolerance
- Distributed Caching
- Distributed Sessions
- Need for Event Driven Systems
- Building Event Driven Systems
- Implementing Distributed Tracing
- Understanding Metrics
- Monitoring Microservices
- Spring Boot Admin
