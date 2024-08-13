# Go Web Server and RSS Scraper

## Overview

The **Go Web Server and RSS Scraper** project is a Go-based application designed to fetch, parse, and serve RSS feeds. It provides a robust web server with modular components for handling various aspects of RSS feed processing, error handling, and user management.

![alt text](./docs/assets/recommender-system.png)

## Tech Stack

- **Go**: Core programming language for implementing the web server and RSS scraper.
- **PostgreSQL**: Database management system for storing RSS feed data.
- **Gin**: Web framework for building the RESTful API.
- **Gorm**: ORM for database interactions.
- **Docker**: Containerizes the application for consistent deployment.
- **GitHub Actions**: Automates CI/CD pipeline for the project.
- **Kubernetes**: Orchestrates containerized application deployment.
- **Prometheus & Grafana**: Used for monitoring and logging application performance.

## Pipeline Flow

- **Data Collection**: Fetches and parses RSS feeds from various sources.
- **API Endpoints**: Provides RESTful endpoints to interact with the feed data.
- **Error Handling**: Robust error handling and logging for reliability.
- **Containerization**: Containerizes the application using Docker.
- **CI/CD Pipeline**: 
  - **Code Commit & Push**: Code is pushed to the GitHub repository.
  - **GitHub Actions Trigger**: GitHub Actions triggers the pipeline upon code push.
  - **Build & Test**: Builds the application and runs tests.
  - **Docker Build**: Builds a Docker image of the application.
  - **Push Docker Image**: Pushes the Docker image to a container registry.
  - **Deploy to Kubernetes**: Deploys the application to a Kubernetes cluster.
  - **Monitoring & Logging**: Uses Prometheus and Grafana for monitoring and logging the application’s performance.

## Installation

For installation steps and configuration details, refer to the [installation guide docs](./docs/installation.md).
