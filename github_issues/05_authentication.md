# Add authentication components and logic

**As a** user
**I need** to register, log in, and update my profile
**So that** I can securely access and manage my GiftLink account

### Details and Assumptions
* Registration and login use JWT for authentication
* Frontend has RegisterPage and LoginPage components
* Backend authRoutes.js implements register, login, and update user APIs

### Acceptance Criteria
```gherkin
Given I am on the registration page
When I submit valid credentials
Then my account is created and I can log in and update my profile
```

**Suggested label:** `backlog`
