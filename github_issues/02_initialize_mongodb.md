# Initialize and populate MongoDB

**As a** developer
**I need** to set up MongoDB and import gift data
**So that** the application has items to display to users

### Details and Assumptions
* MongoDB stores data in the `giftdb` database
* The `gifts` collection holds household item documents
* 16 gift documents are imported from `gifts.json` using the import script

### Acceptance Criteria
```gherkin
Given MongoDB is running and configured
When I run the import script in util/import-mongo
Then 16 documents are inserted into the gifts collection
```

**Suggested label:** `backlog`
