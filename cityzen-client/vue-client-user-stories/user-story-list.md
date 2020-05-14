
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
- as an authenticated user, I should be able to accept a task (should it add user acceptance to backend?)
- as an authenticated user, with an accepted task, I should be able to mark the task complete (should hours be added here?)
- as an authenticated user, I should be able to list my accepted/completed tasks
#### admin users
- as an admin user, I should be able to see a list of users
- as an admin user, with a user record, I should be able to edit notes for the user
- as an admin user, I should be able to see accepted/completed tasks for a specific user
- as an admin user, with a user that has a completed task, I should be able to mark work approved
- as an admin user, with a user that has a completed task, I should be able to make notes on the user_task
- as an admin user, I should be able to get a report of all users and their accepted/completed tasks for a time period
- as an admin user, I should be able to get a report of a specific user's accepted/completed tasks for a time period
- as an admin user, I should be able to add a task (depending on site/implementation?)
#### client/api interaction
- when a user accepts a task, the backend should be updated with the assignment
- when a task is marked complete, the backend should be updated with the status