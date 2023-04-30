# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]

- CI/CD through GitHub Actions
- Monitoring and logging
- Grafana dashboard
- Cluster deployment (Docker Swarm / Kubernetes)
- Kong config

## [1.0.0] - 2023-04-30

### Added

- Tudor Niculescu: Implemented Authenticator microservice that validates user auth tokens with Firebase
- Tudor Pescaru: Implemented sending auth tokens from the mobile client to the backend for validation
- Tudor Pescaru: Implemented connections from CoreBE service to Parser and Authenticator services
- Tudor Niculescu: Added PgAdmin to infra stack and deployed on local environment
- Matei Iordache: Added Prometheus to infra stack and deployed on local environment
- Matei Iordache: Implemented basic logging on BE
- Tudor Pescaru: Added BE microservices to infra stack
- Tudor Pescaru: Added Portainer to infra stack
- Tudor Pescaru: Added basic Kong configuration to infra stack
- Tudor Pescaru: Deployed and tested full stack on local environment

### Fixed

- Tudor Pescaru: Fixed Firebase app config in Authenticator

### Changed

- Tudor Pescaru: Extracted parser code to separate microservice
- Matei Iordache: Started new Infra repo and moved exiting DB Docker setup

### Removed

- Tudor Pescaru: Removed old DB Docker setup from CoreBE repo

## Repositories

[CalendarParserDocs (this changelog)](https://github.com/BitByeBit/CalendarParserDocs)
[CalendarParserInfra](https://github.com/BitByeBit/CalendarParserInfra)
[CalendarParserMobileFE](https://github.com/BitByeBit/CalendarParserMobileFE)
[CalendarParserCoreBE](https://github.com/BitByeBit/CalendarParserCoreBE)
[CalendarParserParser](https://github.com/BitByeBit/CalendarParserParser)
[CalendarParserAuthenticator](https://github.com/BitByeBit/CalendarParserAuthenticator)

