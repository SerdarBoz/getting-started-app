# CI/CD Getting Started App

## Doel
Deze repository bevat een eenvoudige Node.js applicatie met een CI/CD pipeline.
Het doel is om bij elke wijziging automatisch een Docker image te builden en te publiceren.

## Applicatie
De applicatie is gebaseerd op de officiële Docker *Getting Started* tutorial:
https://docs.docker.com/get-started/

## Technologieën
- Node.js
- Docker
- GitHub Actions
- GitHub Container Registry (GHCR)

## CI/CD Werking
Bij elke push naar de `main` branch wordt via een GitHub Actions workflow:
1. De repository uitgecheckt
2. Een Docker image gebouwd
3. De image automatisch gepubliceerd naar GitHub Packages (GHCR)

## Resultaat
- Werkende GitHub Action (minstens 1 succesvolle run)
- Docker image gepubliceerd via GitHub Packages
- Elke codewijziging triggert automatisch een nieuwe image