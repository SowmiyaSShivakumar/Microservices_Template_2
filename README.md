# Microservices_Template_2
This template contains a microservices architecture with an API Gateway, Service Registry, and a User Service.

## Services
- **API Gateway**: Handles incoming requests and routes them to the appropriate service.
- **Service Registry**: Keeps track of all available services.
- **User Service**: A basic service that provides user-related endpoints.

## Setup
1. Clone this repository.
2. Navigate to the directory and build the services using Maven.
3. Run `docker-compose up` to start all services.
4. Access the API Gateway at `http://localhost:8080/users`.
