# Personal Finance Tracker API

A scalable, secure RESTful API for tracking personal transactions and generating financial insights. Built with modern Python tools to demonstrate backend engineering principles: clean architecture, authentication, database persistence, containerization, and cloud deployment.

Inspired by real-world fintech needs designed to handle thousands of transactions with fast analytics while prioritizing security and maintainability.

## Features
- User registration & login with JWT authentication
- CRUD operations for financial transactions
- Analytics endpoints (spending by category, monthly trends)
- PostgreSQL persistence
- Containerized with Docker
- Deployed on AWS (live URL coming soon)

## Tech Stack
- **Backend**: Python 3.11+ with FastAPI (async, automatic OpenAPI docs)
- **Database**: PostgreSQL + SQLAlchemy ORM
- **Auth**: JWT (python-jose) + password hashing (passlib)
- **Containerization**: Docker + Docker Compose
- **Deployment**: AWS (EC2/Lightsail)
- **Testing**: pytest
- **Other**: Pydantic for validation, python-dotenv for config

## Architecture Overview
[Insert diagram here later – FastAPI → PostgreSQL → Docker → AWS]

## Local Development

1. Clone and enter repo
   ```bash
   git clone https://github.com/BenjaminxCoder/personal-finance-tracker-api.git
   cd personal-finance-tracker-api