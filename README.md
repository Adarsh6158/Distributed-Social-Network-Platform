<h1 align="center">Distributed Social Networking Platform</h1>

<p align="center">
  A LinkedIn-like social network built using Spring Boot microservices, Kafka, and an API Gateway.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Architecture-Microservices-blue" />
  <img src="https://img.shields.io/badge/Event%20Driven-Kafka-red" />
  <img src="https://img.shields.io/badge/Backend-SpringBoot-green" />
  <img src="https://img.shields.io/badge/Database-PostgreSQL%20%7C%20Neo4j-orange" />
</p>


## Core Features

* Authentication with JWT
* Post creation and interactions (likes)
* Connection management using Neo4j
* Event-driven notifications using Kafka
* API Gateway for centralized routing
* Service discovery using Eureka


## Architecture

### System Overview

<img width="650" height="370" alt="image" src="https://github.com/user-attachments/assets/77f5e2c0-aaa4-462e-82da-5e14dd4e0775" />


### Service Interaction Flow

<img width="910" height="590" alt="image" src="https://github.com/user-attachments/assets/d2b4e220-2cf4-45a7-a4f8-df1fb0255ff2" />



### Database Design

<img width="900" height="510" alt="image" src="https://github.com/user-attachments/assets/9a6345ca-f85e-4cff-a4b4-ab02e21dd960" />


## Tech Stack

<table>
<tr>
<td>

<b>Backend</b><br/> <img src="https://www.vectorlogo.zone/logos/java/java-icon.svg" width="28"/> Java   <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" width="28"/> Spring Boot   <img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-icon.svg" width="28"/> Kafka

</td>

<td>

<b>Databases</b><br/> <img src="https://www.vectorlogo.zone/logos/postgresql/postgresql-icon.svg" width="28"/> PostgreSQL   <img src="https://www.vectorlogo.zone/logos/neo4j/neo4j-icon.svg" width="28"/> Neo4j

</td>
</tr>

<tr>
<td>

<b>Cloud & DevOps</b><br/> <img src="https://www.vectorlogo.zone/logos/docker/docker-icon.svg" width="28"/> Docker   <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" width="28"/> Kubernetes

</td>

<td>

<b>Observability</b><br/> <img src="https://www.vectorlogo.zone/logos/elastic/elastic-icon.svg" width="28"/> ELK Stack   <img src="https://www.vectorlogo.zone/logos/zipkinio/zipkinio-icon.svg" width="28"/> Zipkin

</td>
</tr>
</table>


## Design Highlights

* Each service owns its database (no shared schema)
* Kafka enables loose coupling and async workflows
* Neo4j is used for efficient relationship queries
* Services are independently scalable



## Why this project

Built to understand how real distributed systems are designed, how services communicate, and how systems scale in production environments.
