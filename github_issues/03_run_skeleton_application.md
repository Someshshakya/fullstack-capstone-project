# Run skeleton application

**As a** developer
**I need** to run the GiftLink skeleton application locally
**So that** I can verify the project structure and begin development

### Details and Assumptions
* Backend runs on port 3060
* Frontend runs on the default React development port
* Environment variables are configured in `.env` files

### Acceptance Criteria
```gherkin
Given dependencies are installed with npm install
When I start the backend and frontend servers
Then both applications run without errors
```

**Suggested label:** `backlog`
