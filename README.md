# test-monorepo

This repository is a Gradle multi-module monorepo for Spring Boot microservices.

## Modules
- `platform/` → Internal BOM (Java Platform) with dependency versions
- `services/test-1-service` → Spring Boot microservice
- `services/test-2-service` → Spring Boot microservice
- `services/test-3-service` → Spring Boot microservice
- `services/test-4-service` → Spring Boot microservice
- `azure-pipelines/azure-pipelines.yml` → Azure DevOps CI/CD pipeline