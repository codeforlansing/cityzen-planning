
### Title: Client retrieves current list of tasks
- Priority:
- Estimate:
- Assinged:
- Status:
#### Details:
- As a <valid_client>
- I want to retrieve a list of available tasks
- so that I can see what volunteer tasks are available
#### Acceptance Criteria
- [ ] Given a valid client, when the current available task list is requested, Then:
  - [ ] A list of tasks is returned
  - [ ] All available tasks are contained in the resoponse
  - [ ] No tasks that are already complete/accepted are in the response
#### Notes  
- through an ORM is prefered
- currently SQL backed by sqlite 