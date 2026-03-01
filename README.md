# study_forge_backend_Docker
A production-structured backend application built using Node.js and Express with a Dockerized PostgreSQL database. The project demonstrates full CRUD REST API development, environment variable configuration, secure SQL queries, and container-based database management.
Project Overview

Study Forge Backend is a production-structured RESTful API built using Node.js, Express.js, and a Dockerized PostgreSQL database.

This project demonstrates backend development fundamentals including API routing, database integration, environment variable management, containerized database setup, and full CRUD (Create, Read, Update, Delete) operations.

The database is managed inside a Docker container to ensure isolated, portable, and consistent development environments — reflecting real-world backend deployment practices.

 Features

Create Notes (POST)

Read All Notes (GET)

Update Existing Notes (PUT)

Delete Notes (DELETE)

Secure parameterized SQL queries

Docker-based PostgreSQL setup

Environment variable configuration using dotenv

Clean and structured backend architecture

🛠 Tech Stack

Node.js – Backend runtime environment

Express.js – Web framework for building REST APIs

PostgreSQL – Relational database

Docker – Containerized database environment

dotenv – Environment variable management

 What This Project Demonstrates

This project showcases:

Building REST APIs from scratch

Connecting Node.js to PostgreSQL

Using Docker for database containerization

Handling request parameters and JSON body parsing

Implementing secure SQL queries using placeholders

Understanding backend request-response lifecycle

Structuring backend applications professionally

It reflects real-world backend workflows where the application server and database run as separate services.

 Why Docker Was Used

Instead of installing PostgreSQL directly on the system, Docker was used to:

Isolate the database environment

Avoid dependency conflicts

Maintain version consistency

Simulate production-like backend architecture

Easily start/stop database containers

This mirrors modern DevOps practices used in industry.
