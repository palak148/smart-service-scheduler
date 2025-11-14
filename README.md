Smart Service Scheduler

A microservices-based Spring Boot project for booking and managing home or office services.
This platform provides user management, service catalog, booking flow, scheduling, and notifications with a scalable architecture ready for cloud deployment.

🚀 Project Overview

Smart Service Scheduler is a real-world style application where users can book professional services like plumbing, electrician, cleaning, AC repair, etc.
The system handles:

User registration & authentication

Service catalog display

Booking services with time slots

Notification system

Microservice communication

Cloud-ready, container-ready architecture

🧱 Microservices Architecture
smart-service-scheduler/
│
├── user-service/              # Handles users & authentication
├── service-catalog-service/   # Manages service listings
├── booking-service/           # Booking & scheduling flow
├── notification-service/      # Email / message notifications
├── api-gateway/               # Central entry point
└── discovery-server/          # Eureka service discovery


Each service runs independently and communicates using REST + Feign Client.

⚙️ Tech Stack
Backend

Java 17

Spring Boot

Spring Cloud (Gateway, Eureka, Config)

Spring Data JPA

Hibernate

Feign Client

Database

MySQL (for each service or shared initially)

Dev Tools

Maven

Postman

Docker (future)

AWS (future deployment)

🧩 Features

Create/manage users

Browse available services

Book a service

Real-time scheduling

Notifications

Role-based access (Admin & User)

Load-balanced microservices

Gateway routing

Cloud-native structure
