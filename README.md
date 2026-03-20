# NexOrder - Microservices-Based Order Management System

NexOrder is a scalable, microservices-based backend system designed to
simulate a real-world e-commerce/order management platform. It
demonstrates modern backend engineering practices using .NET,
containerization, cloud deployment, and distributed system design.

------------------------------------------------------------------------

## 🚀 Key Features

-   Microservices-based architecture
-   RESTful APIs using .NET
-   API Gateway with JWT authentication
-   Role-based access control (RBAC)
-   Docker containerization
-   Unified Docker Compose setup for local orchestration
-   CI/CD pipeline using GitHub Actions
-   Deployment to Azure Web App for Containers
-   Scalable and production-ready design principles

------------------------------------------------------------------------

## 🏗️ Architecture Overview

The system follows a microservices architecture where each service is
independently developed, deployed, and scaled.

### Core Services

-   ProductService -- Manages product catalog
-   OrderService -- Handles order processing
-   AuthService -- Handles authentication (JWT-based)
-   API Gateway -- Central entry point for all client requests

------------------------------------------------------------------------

## 🔐 Authentication & Authorization

-   Authentication is handled using JWT tokens
-   Token validation is performed at the API Gateway level
-   Only authenticated requests are forwarded to microservices
-   Services implement role-based authorization using claims

Flow: Client → API Gateway → Microservices

------------------------------------------------------------------------

## 🐳 Containerization & Local Orchestration

NexOrder supports full containerization using Docker, with a unified
Docker Compose setup.

Run all services: docker compose up --build

------------------------------------------------------------------------

## ☁️ Deployment

-   GitHub Actions builds Docker images
-   Deployed to Azure Web App for Containers

------------------------------------------------------------------------

## 📦 Technologies Used

-   .NET (Web API)
-   Docker & Docker Compose
-   Azure
-   GitHub Actions
-   JWT Authentication

------------------------------------------------------------------------

## 📌 How to Use

1.  Clone repository
2.  Run: docker compose up --build
