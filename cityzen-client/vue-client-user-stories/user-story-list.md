
### webclient (unauthenticated users)
- as a user, I should be able to register for an account
- as a user, I should be able to authenticate internally to client on local network
- as a user, I should be able to authenticate from the internet
- as a user, I should be able to see available volunteer tasks
- as a user, I should be able to accept a task with a user_code, username, or email when unauthenticated user actions are allowed
- as a user, I should be able to mark a task complete with a user code (and hours worked?) when unauthenticated user actions are allowed
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