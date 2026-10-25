# spring-ai-mcp-server

spring-ai-mcp-server is a lightweight Spring Boot skeleton project intended as the starting point for building an AI MCP (Model Control Plane) server. It provides a minimal structure with a health endpoint, actuator support, and a Maven build configuration.

Features
- Spring Boot 3.x
- REST controller with a health endpoint (/api/health)
- Actuator enabled for health and info
- Maven build (jar)

Getting started
1. Build:
   mvn clean package

2. Run:
   java -jar target/spring-ai-mcp-server-0.0.1-SNAPSHOT.jar

3. Health endpoint:
   GET http://localhost:8080/api/health

Notes
- This repository is a public skeleton to be extended with AI-specific MCP functionality such as model registration, versioning, inference routing, and telemetry.
- Modify groupId and package names as needed for your organization.

License
This project is provided as-is. Add a license file if you intend to apply one.