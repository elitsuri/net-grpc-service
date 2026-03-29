# .NET gRPC Service

> gRPC service with .NET, Protobuf, and PostgreSQL

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
.NET, C#, ASP.NET Core, PostgreSQL, EF Core, Docker

## 🏗️ Architecture
Backend service with .NET, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/.net-grpc-service
cd .net-grpc-service

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
