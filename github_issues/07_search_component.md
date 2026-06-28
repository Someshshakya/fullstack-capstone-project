# Implement a search component

**As a** user
**I need** to search and filter gifts by category, condition, and age
**So that** I can quickly find items that match my preferences

### Details and Assumptions
* Search page connects to `/api/search` endpoint
* Filters include name, category, condition, and age range
* Results update based on selected filter criteria

### Acceptance Criteria
```gherkin
Given I am on the search page
When I filter by category and click search
Then I see only gifts matching the selected category
```

**Suggested label:** `backlog`
