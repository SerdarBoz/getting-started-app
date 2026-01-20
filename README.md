# Getting started

This repository is a sample application for users following the getting started guide at https://docs.docker.com/get-started/.

The application is based on the application from the getting started tutorial at https://github.com/docker/getting-started

# CI/CD Getting Started App

## Doel
Deze repository bevat een eenvoudige Node.js applicatie met een CI/CD pipeline.

## Technologieën
- Node.js
- Docker
- GitHub Actions
- GitHub Container Registry (GHCR)

## CI/CD Werking
Bij elke push naar de `main` branch:
1. Wordt automatisch een Docker image gebouwd
2. Wordt de image gepubliceerd naar GitHub Packages

## Resultaat
- Werkende GitHub Action (minstens 1 succesvolle run)
- Gepubliceerde Docker image zichtbaar in GitHub Packages
