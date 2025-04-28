# Federated_Database_Healthcare_Insurance_Integration
# Healthcare and Insurance Integration System

A federated database application that bridges the gap between healthcare providers and insurance companies using SQL Server and Neo4j.

## Features

- **Federated Database Architecture**: Combines SQL Server (relational) and Neo4j (graph) databases
- **Role-Based Access**: Separate portals for healthcare and insurance professionals
- **Complete Patient Views**: Unified patient information across medical and insurance systems
- **Full CRUD Operations**: Comprehensive data management for all entities
- **RESTful API**: Clean, well-documented API for system interactions

## Technology Stack

- **Backend**: Python, FastAPI, SQLAlchemy, Neo4j Python Driver
- **Frontend**: React, React Router, CSS
- **Databases**: Microsoft SQL Server, Neo4j Graph Database
- **Authentication**: JWT-based authentication with role-based permissions

## System Architecture

This system uses a federated database approach that:
1. Stores patient and medical data in SQL Server
2. Manages insurance policies and claims in Neo4j
3. Unifies data through a consistent API layer

## Installation & Setup

1. Clone the repository
2. Set up SQL Server and Neo4j instances
3. Configure environment variables
4. Install backend dependencies: `pip install -r requirements.txt`
5. Install frontend dependencies: `cd frontend && npm install`
6. Run the backend: `uvicorn main:app --reload`
7. Run the frontend: `cd frontend && npm start`

