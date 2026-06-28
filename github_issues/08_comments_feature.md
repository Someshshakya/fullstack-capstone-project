# Design and implement the comments feature

**As a** user
**I need** to leave comments on gift items
**So that** I can ask questions or provide feedback about an item

### Details and Assumptions
* Comments are associated with a specific gift item
* Sentiment analysis can be applied to comment text
* Authenticated users can post comments

### Acceptance Criteria
```gherkin
Given I am viewing a gift item
When I submit a comment
Then my comment is saved and displayed on the item details page
```

**Suggested label:** `icebox`
