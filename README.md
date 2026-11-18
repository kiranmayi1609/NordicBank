# NordicBank – Digital Banking Platform

A modern full-stack digital banking platform built with React, TypeScript, ASP.NET Core Web API and PostgreSQL.

## Overview

NordicBank is a full-stack digital banking application designed to demonstrate the development of a modern banking platform, combining a responsive user interface with a robust backend and relational database.

The platform aims to provide customers with an intuitive experience for managing accounts, viewing balances, reviewing transaction history and performing simulated money transfers.

The project emphasizes clean architecture, secure application development, RESTful API design, database management, maintainable code and a professional user experience.

## Key Features

The following features are planned for the platform:

- Customer registration and authentication
- Secure login and account access
- Personal banking dashboard
- Account and balance management
- Transaction history and filtering
- Simulated money transfers
- Input validation and error handling
- Role-based authorization
- Administrative dashboard
- Audit logging

## Technology Stack

| Area | Technologies |
|---|---|
| Frontend | React, TypeScript, Vite |
| Backend | C#, ASP.NET Core Web API |
| Database | PostgreSQL |
| ORM | Entity Framework Core |
| API Documentation | Swagger / OpenAPI |
| Version Control | Git, GitHub |
| Development Environment | Visual Studio Code |

## Architecture

NordicBank follows a client-server architecture with three main layers:

**Frontend**
- Responsive banking interface
- Customer dashboard and account management
- Communication with backend APIs

**Backend**
- RESTful API endpoints
- Banking business logic
- Authentication and authorization
- Input validation and error handling

**Database**
- Customer information
- Bank accounts
- Transaction records
- Relational data management

## Project Structure

```text
NordicBank/
│
├── frontend/
│   └── nordicbank-web/
│       ├── src/
│       ├── public/
│       └── package.json
│
├── backend/
│   └── NordicBank.Api/
│       ├── Program.cs
│       └── NordicBank.Api.csproj
│
├── database/
├── docs/
├── tests/
│
├── README.md
└── .gitignore
```

## Getting Started

### Prerequisites

Install the following tools before running the application:

- Node.js
- npm
- .NET SDK
- PostgreSQL
- Git

### Frontend Setup

```bash
cd frontend/nordicbank-web
npm install
npm run dev
```

### Backend Setup

```bash
cd backend/NordicBank.Api
dotnet restore
dotnet run
```

The frontend and backend run as separate applications during local development.

### API Documentation

Swagger / OpenAPI documentation will be available when API documentation is configured and the backend is running.

## Security

Security is a core consideration in the development of NordicBank.

Planned security practices include:

- Password hashing
- Authentication and authorization
- Role-based access control
- Server-side input validation
- Secure configuration and secret management
- Audit logging

## Development Roadmap

The project is being developed in the following phases:

1. Project setup and configuration
2. Database design and integration
3. Core banking API development
4. Frontend development
5. Banking functionality
6. Security and administration
7. Testing, documentation and deployment

## Testing

Automated testing will cover relevant application components, API functionality and business logic as development progresses.

## Screenshots

Application screenshots and demonstrations will be added as features are implemented.

## Deployment

Deployment configuration and live application links will be added after the application is ready for production-style demonstration.

## Disclaimer

NordicBank is a demonstration digital banking platform. It uses simulated customer, account and transaction data. It does not connect to real financial institutions or process real financial transactions.

## Author

Developed as a full-stack software engineering portfolio project.
