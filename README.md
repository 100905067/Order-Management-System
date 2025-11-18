# Order-Management-System
This is a microservices-based backend project built with Java and Spring Boot, demonstrating event-driven architecture using Kafka. The system consists of two services:  Order Service – Accepts and stores orders, then publishes order events to Kafka.  Inventory Service – Listens to order events and updates product inventory accordingly.

# Check the health of application
curl http://localhost:8080/actuator/health "or"
http://localhost:8080/actuator/health in browser


# Run the application on windows
cd order-service
./mvnw spring-boot:run



