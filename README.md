# spring-boot-microservice-sample
**Eureka Server**
  1.Eureka Server is a centralized registry that maintains a list of all the registered services and their instances. 
  2.Every Micro service will register into the Eureka server and Eureka server knows all the client applications running on each port and IP address. Eureka Server is also known as Discovery Server.
  **Required annotation**
  -->@EnableEurekaServer
  **Application properties**
  server.port = 8761
