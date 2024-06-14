# Microservices-Based E-commerce Platform

## Description

This project is an architected Microservices Platform for an e-commerce application with various functionalities including:
- Login and Authorization
- Product Catalog
- Payment Gateway Integration (Razorpay, Stripe)
- Service Discovery
- Notification Service (Email Notification)

The entire ecosystem is deployed on AWS Elastic Beanstalk leveraging RDS for data persistence and CloudWatch for efficient logging and monitoring.

Key features:
- Event Driven Email Service using Kafka for large-scale email distribution across different services.
- Powerful sorting, filtering, and paging for efficient product discovery.
- Optimized API response times from ~500 ms to ~20 ms using Redis Cache for static data caching.

## Microservices Code Links

- **Ecommerce Product Service:** [Here](https://github.com/dhanushdh01/E-ComProductService/tree/main/EcomProductService)
- **User Authorization Service:** [Here](https://github.com/dhanushdh01/EcomUserAuthService/tree/main/EcomUserAuthService)
- **Payment Gateway Service:** [Here](https://github.com/dhanushdh01/E-Com-Payment-Service/tree/main/PaymentService)
- **Email Notification Service:** [Here](https://github.com/dhanushdh01/EmailService)
- **Service Discovery Eureka client:** [Here](https://github.com/dhanushdh01/ServiceDiscovery)
- **Eureka Server:** [Here](https://github.com/dhanushdh01/Eureka-Server/blob/main/README.md)

## Tools and Frameworks Used

- **Backend:** Java, SpringBoot, SpringCloud
- **Database:** MySQL, Hibernate
- **Caching:** Redis
- **Payment Gateways:** Razorpay, Stripe, OR we can add more Gateways
- **Testing:** JUnit
- **Messaging:** Kafka
- **Deployment:** AWS Elastic Beanstalk, RDS, CloudWatch

## Features

- **Login and Authorization:** Secure login and user management using a dedicated User Authorization Service.
- **Product Catalog:** Comprehensive product catalogue with advanced sorting, filtering, and paging.
- **Payment Gateway Integration:** Seamless integration with Razorpay and Stripe for payment processing.
- **Service Discovery:** Implemented using Eureka client for efficient service discovery and load balancing.
- **Notification Service:** Robust email notification service using Kafka for event-driven communication.
- **Caching:** Utilized Redis for caching static data, significantly improving API response times.

## Deployment

The microservices are deployed on AWS Elastic Beanstalk, utilizing AWS RDS for data persistence and CloudWatch for logging and monitoring.

## Optimizations

- **API Response Time:** Improved from ~500 ms to ~20 ms by caching static data using Redis Cache.

---

Feel free to explore the code repositories linked above for more detailed implementation and configuration of each microservice.

