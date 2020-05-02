# spring-microservices
Spring Microservices, created and deployed on multriple instances using Spring Boot and Spring Cloud

The project is implemented using the following technologies : 
Spring, SpringBoot, Spring Cloud, Spring Data

The project Mainly contains 4 services :

1. Product Service: Main service, which offers a REST API to list a list of products.
2. Config Service: Conguration service, whose role is to centralize the configuration files from different microservices in one place.
3. Proxy Service: Gateway responsible for routing a request to one instances of a service, so as to automatically manage the load-balancing.
4. Discovery Service: Service allowing the recording of instances of services to be discovered by other services.
