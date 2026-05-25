# E-Shop Microservices

A learning project for building an e-commerce application using a microservices architecture with .NET.

## Project Goal

The goal of this project is to practise building a real-world e-commerce system step by step, including product catalog, basket, ordering, authentication, messaging, caching, and containerisation.

## Planned Architecture

This project will be split into independent services. Each service will own its own responsibility and data.

### Planned Services

- **Catalog Service** - manages products, categories, and product details.
- **Basket Service** - manages customer shopping baskets.
- **Ordering Service** - handles orders and order history.
- **Payment Service** - payment integration placeholder for future implementation.
- **Identity Service** - authentication and authorization.

## Planned Technologies

- .NET / ASP.NET Core Web API
- PostgreSQL
- Entity Framework Core
- Redis
- RabbitMQ
- MassTransit
- Docker
- Keycloak / OpenID Connect
- CQRS
- MediatR
- Vertical Slice Architecture
- Domain-Driven Design concepts
- Outbox Pattern

## Current Status

This repository is currently in the initial setup stage.

Planned next steps:

1. Create the solution structure.
2. Add the Catalog microservice.
3. Configure PostgreSQL database support.
4. Add Basket service.
5. Add Redis caching.
6. Add RabbitMQ and MassTransit messaging.
7. Add Docker support.
8. Add authentication and authorization.

## How to Run

Instructions will be added after the first service is created.

Expected future command:

```bash
dotnet run
