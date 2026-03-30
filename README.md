# Module 9 - FastAPI, PostgreSQL, and pgAdmin

This project is a FastAPI calculator application running with PostgreSQL and pgAdmin using Docker Compose. The goal of the project is to practice working with a containerized database environment and use raw SQL in pgAdmin to create, insert, query, update, and delete records.

## Tech Stack

- FastAPI
- PostgreSQL
- pgAdmin
- Docker Compose
- Pytest
- GitHub Actions

## Project Purpose

This project demonstrates how to:

- run a FastAPI app, PostgreSQL database, and pgAdmin together with Docker Compose
- connect to PostgreSQL through pgAdmin
- perform basic SQL operations
- work with a one-to-many relationship using foreign keys

## How to Run the Project

From the project root, run:

```bash
docker compose up --build