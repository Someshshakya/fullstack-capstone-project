# Implement Gifts details page

**As a** user
**I need** to view detailed information about a gift item
**So that** I can decide whether to request or pick up the item

### Details and Assumptions
* Details page fetches a single gift by ID from `/api/gifts/:id`
* Page displays name, category, condition, age, and description
* User can navigate to details from the main listings page

### Acceptance Criteria
```gherkin
Given I am on the main listings page
When I click on a gift item
Then I see the full details of that gift on the details page
```

**Suggested label:** `backlog`
