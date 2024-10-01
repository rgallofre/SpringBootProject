# SpringBootProject

## Description
SPRINGBOOTPROJECT is a Spring Boot application developed in Eclipse. The primary focus of this project is to build a RESTful web service. This service exposes REST APIs to handle requests and responses for various endpoints. It provides a clean and scalable foundation for creating and deploying REST services using the Spring Boot framework.

## Features
- Developed with Spring Boot and Java.
- RESTful services for handling HTTP requests.
- Easy to configure and deploy.
- Scalable for future enhancements.

## Technologies Used
- **Java**: Core language for development.
- **Spring Boot**: Main framework for building the RESTful service.
- **Maven**: Dependency management and build tool.
- **Eclipse**: IDE for development.

## REST API Endpoints

Below are the basic RESTful API endpoints provided by the application:

### Instructions
### 1. GET Request

$ curl -v localhost:8080/employees | json_pp
$ curl -v localhost:8080/employees/{id}

### 2. **POST Request**

$curl -X POST localhost:8080/employees -H 'Content-type:application/json' -d '{"name": "{name}", "role": "{role}'}'

### 3. **PUT Request**
$ curl -v -X PUT localhost:8080/employees/{id} -H 'Content-Type:application/json' -d '{"name": "{name}", "role": "{role}}' | json_pp

### 4. **DELATE Request**
$ curl -v -X DELETE localhost:8080/employees/{id}

### **ORDERS**
### 1. **GET Request**
$ curl -v http://localhost:8080/orders | json_pp
$ curl -v http://localhost:8080/orders/{id} | json_pp

### 2. **PUT Request**
$ curl -v -X PUT localhost:8080/orders/4/complete | json_p

### 3. **DELATE Request**

$ curl -v -X DELETE http://localhost:8080/orders/{id}/cancel | json_pp





