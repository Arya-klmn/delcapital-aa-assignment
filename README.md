# Account Aggregator Integration

## Overview

This project implements a simplified Account Aggregator (AA) integration for Financial Information User (FIU) workflows. The application enables customers to provide consent for sharing financial information, tracks the consent lifecycle, retrieves financial data from Financial Information Providers (FIPs), and stores audit-compliant records for downstream services.

The solution is built using Spring Boot, PostgreSQL, and Angular, following a layered architecture with a focus on security, maintainability, and scalability.

## Features

* Consent Creation and Management
* Consent Status Tracking
* Financial Data Retrieval
* Data Normalization Layer
* Audit Logging
* RESTful APIs
* PostgreSQL Persistence
* Angular Frontend Dashboard
* Swagger API Documentation

## Architecture

Frontend (Angular)
↓
Backend (Spring Boot)
↓
Account Aggregator / Digio Integration Layer
↓
Financial Information Providers (FIPs)

PostgreSQL Database

## Tech Stack

### Backend

* Java 21
* Spring Boot 3
* Spring Data JPA
* PostgreSQL
* Maven
* Lombok

### Frontend

* Angular
* Angular Material
* TypeScript

### Database

* PostgreSQL

## Modules

### Consent Management

Handles creation, tracking, and management of customer consent requests.

### Financial Data Service

Retrieves and stores financial information associated with approved consents.

### Audit Logging

Maintains a complete audit trail of consent and data retrieval activities.

### API Layer

Exposes REST endpoints for consent management, status tracking, and data retrieval.

## Security Considerations

* Input Validation
* Layered Architecture
* Secure Credential Management
* Audit Logging
* Minimal PII Storage
* HTTPS-ready Configuration

## Future Enhancements

* Complete Digio Sandbox Integration
* Webhook-based Consent Updates
* Retry and Circuit Breaker Mechanisms
* Role-Based Access Control
* Monitoring and Observability
* Containerized Deployment using Docker

## Author

Arya Kummari

B.Tech Civil Engineering, IIT Madras
