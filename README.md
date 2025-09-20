# 🚀 Microservices-based Hotel Management System  

This repository contains a complete *Microservices Architecture implementation using Spring Boot*.  
The system demonstrates a real-world *Hotel Management Platform*, where different services handle users, hotels, and ratings independently.  

The architecture is designed with *scalability, fault tolerance, security, and centralized configuration* in mind.  

---

## 📌 Features  

### 🏗 Core Microservices  
- *User Service* – manages users and their details  
- *Hotel Service* – handles hotel data and operations  
- *Rating Service* – manages ratings and reviews for hotels  

### 🔍 Service Discovery & Communication  
- *Eureka Server* for service registry  
- Service-to-service communication using *Feign Client* and *RestTemplate*  
- Dynamic service discovery without hardcoding host/port  

### 🌐 API Gateway  
- Built with *Spring Cloud Gateway*  
- Central entry point for all microservices  
- Supports multiple route configurations  

### ⚙ Centralized Configuration  
- *Spring Cloud Config Server* for externalized configuration management  
- Config Clients implemented across services  

### 🛡 Resilience & Fault Tolerance  
- *Resilience4j* integration for:  
  - Circuit Breaker  
  - Retry Mechanism  
  - Rate Limiting  
- Ensures fault tolerance and better stability under load  

### 🔒 Security  
- *Spring Security with OKTA Authentication*  
- Secure login and authorization flows  
- Security enforced at API Gateway and individual services  
- Feign Interceptor & RestTemplate client with security handling  

---

## ⚙ Tech Stack  

- *Java 17+*  
- *Spring Boot*  
- *Spring Cloud* (Eureka, Config, Gateway)  
- *Resilience4j* (Circuit Breaker, Retry, Rate Limiter)  
- *Feign Client & RestTemplate*  
- *Spring Security + OKTA*  
- *Maven* (Build Tool)  

---

## 📂 Project Structure  

bash
microservices-hotel-app/
├── apache-jmeter-5.5/        # Performance testing setup using JMeter
├── ApiGateway/               # Spring Cloud API Gateway
│   └── ApiGateway/
├── ConfigServer/             # Centralized configuration server
│   └── ConfigServer/
├── HotelService/             # Manages hotel data
│   └── HotelService/
├── RatingService/            # Handles ratings & reviews
│   └── RatingService/
├── ServiceRegistry/          # Eureka service registry
│   └── ServiceRegistry/
└── UserService/              # Handles user-related operations



## 🏁 Key Highlights

- Built a scalable microservices ecosystem with Spring Boot
- Implemented service discovery, API gateway, and centralized configuration
- Ensured fault tolerance with resilience patterns (circuit breaker, retry, rate limiter)
- Integrated enterprise-grade security using OKTA
- Developed a real-world Hotel Management System to demonstrate microservices in action

---

## ✅ Conclusion  

This project showcases how a complete *Hotel Management System* can be built using a *Microservices Architecture* with Spring Boot and Spring Cloud.  
It demonstrates the power of *service discovery, centralized configuration, API gateway, fault tolerance, and security* to create a scalable, reliable, and production-ready system.  

Feel free to explore, fork, and enhance this project. 🚀  
Contributions are welcome – let’s build better microservices together! 💡  

---
