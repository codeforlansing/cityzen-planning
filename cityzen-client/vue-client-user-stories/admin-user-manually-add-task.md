as an admin user, I should be able to add a task (depending on site/implementation?)
### Title:
- Priority:
- Estimate:
- Assinged:
- Status:
#### Details:
- As an <admin_user>
- I want to add a new task
- so that I can have it available for users to accept
#### Acceptance Criteria
- [ ] Given a valid admin user, when a task is added through the client, Then:
  - [ ] The new task should be listed in available tasks
  - [ ] The task should be persisted in the back end
#### Notes
- may need capablity to disable in configuration if seperate backend is polled to update available tasks