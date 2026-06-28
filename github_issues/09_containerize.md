# Containerize the services and applications

**As a** developer
**I need** to containerize the backend, frontend, and sentiment services with Docker
**So that** the application can be deployed consistently across environments

### Details and Assumptions
* Each service has its own Dockerfile
* Docker Compose can orchestrate all services together
* MongoDB can run as a container or connect to a cloud instance

### Acceptance Criteria
```gherkin
Given Docker is installed
When I build and run the containers
Then all services start and communicate correctly
```

**Suggested label:** `icebox`
