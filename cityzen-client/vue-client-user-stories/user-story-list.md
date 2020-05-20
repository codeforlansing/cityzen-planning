
### webclient (unauthenticated users)
#### unauthenticated users
##### when unauthenticated actions are allowed
- [able to see available volunteer tasks](unauthenticated-list-available-tasks.md)
- [accept task with user_code, username, or email](unauthenticated-accept-task.md)
- [mark task complete with a user code](unauthenticated-mark-task-complete.md)
##### when configured for authenticated users only
- [register for an account](register-new-user-account.md)
- [authenticate internally to client on local network](authenticate-on-local-network.md)
- [users should be able to authenticate from the internet, when configured](authenticate-from-internet.md)
#### authenticated users 
- definition of authenticated could be site/implementation specific (full login, user code/email, token, etc)
- [authenticated user should be able to accept a task](authenticated-user-accept-task.md)
- [authenticated user should be able to mark accepted task complete](authenticated-user-mark-accepted-task-complete.md)
- [authenticated user should be able to list accepted/completed tasks](authenticated-user-list-accepted-complete-tasks.md)
#### admin users
- [admin user should be able to list users](admin-user-list-users.md)
- [admin user should be able to edit notes for a valid user](admin-user-edit-notes-on-user.md)
- [admin user should be able to list tasks for a specific user](admin-user-list-tasks-single-user.md)
- [admin user should be able to mark completed task approved for a user](admin-user-marks-completed-task-approved.md)
- as an admin user, with a user that has a completed task, I should be able to make notes on the user_task
- as an admin user, I should be able to get a report of all users and their accepted/completed tasks for a time period
- as an admin user, I should be able to get a report of a specific user's accepted/completed tasks for a time period
- as an admin user, I should be able to add a task (depending on site/implementation?)
#### client/api interaction
- when a user accepts a task, the backend should be updated with the assignment
- when a task is marked complete, the backend should be updated with the status