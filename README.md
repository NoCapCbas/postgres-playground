# PostgreSQL Playground

A development environment for PostgreSQL 16 with pgAdmin 4, featuring Docker container networking.

## 🌟 Features

- PostgreSQL 16 database server
- pgAdmin 4 web interface
- Automatic database configuration
- Persistent data storage
- Container networking support

## 🔧 Prerequisites

- Docker
- Docker Compose
- Make (optional, but recommended)

## 🚀 Getting Started

1. Clone the repository
2. Run `make shared-network` to create the shared network
3. Run `make up` to start the containers
4. Access pgAdmin at `http://localhost:5050`
5. Access PostgreSQL at `localhost:5432`

