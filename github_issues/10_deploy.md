# Deploy backend and frontend

**As a** developer
**I need** to deploy the GiftLink application to the cloud
**So that** users can access the application from anywhere

### Details and Assumptions
* Backend deploys to Kubernetes or IBM Code Engine
* Frontend deploys as a serverless application
* CI/CD pipeline runs via GitHub Actions

### Acceptance Criteria
```gherkin
Given the application is containerized
When I deploy to the cloud platform
Then the landing page is accessible via a public URL
```

**Suggested label:** `icebox`
