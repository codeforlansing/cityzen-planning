## Cityzen Clients
- multiple client endpoints expected in future
- client might be: a js widget that shows on any site, wp plugin, mobile app, any other client that can access an API
- currently a vue based webapp is in development for the Fledge
    - external styles should match with [thefledge.com](https://thefledge.com) website style
    - accept task and track without sign-in (user token/id?) some tracking is needed for reporting
- task acceptance should be allowed without login?
- should entry of a valid user token be a form of authentication?  ie: no 'unauthenticated' user actions, just configure what is needed to be 'authenticated'
### [Client User Stories](#user-stories)
### Vue webclient user stories
#### unauthenticated users
##### when unauthenticated actions are allowed
- [able to see available volunteer tasks](vue-client-user-stories/unauthenticated-list-available-tasks.md)
- [accept task with user_code, username, or email](vue-client-user-stories/unauthenticated-accept-task.md)
- [mark task complete with a user code](vue-client-user-stories/unauthenticated-mark-task-complete.md)
##### when configured for authenticated users only
- [register for an account](vue-client-user-stories/register-new-user-account.md)
- [authenticate internally to client on local network](vue-client-user-stories/authenticate-on-local-network.md)
- [users should be able to authenticate from the internet, when configured](vue-client-user-stories/authenticate-from-internet.md)
#### authenticated users 
definition of authenticated could be site/implementation specific (vue-client-user-stories/full login, user code/email, token, etc)
- [authenticated user should be able to accept a task](vue-client-user-stories/authenticated-user-accept-task.md)
- [authenticated user should be able to mark accepted task complete](vue-client-user-stories/authenticated-user-mark-accepted-task-complete.md)
- [authenticated user should be able to list accepted/completed tasks](vue-client-user-stories/authenticated-user-list-accepted-complete-tasks.md)
#### admin users
- [admin user should be able to list users](vue-client-user-stories/admin-user-list-users.md)
- [admin user should be able to edit notes for a valid user](vue-client-user-stories/admin-user-edit-notes-on-user.md)
- [admin user should be able to list tasks for a specific user](vue-client-user-stories/admin-user-list-tasks-single-user.md)
- [admin user should be able to mark completed task approved for a user](vue-client-user-stories/admin-user-marks-completed-task-approved.md)
- [admin user should be able to make notes on completed user task](vue-client-user-stories/admin-user-make-completed-task-notes.md)
- as an admin user, I should be able to get a report of all users and their accepted/completed tasks for a time period
- as an admin user, I should be able to get a report of a specific user's accepted/completed tasks for a time period
- as an admin user, I should be able to add a task (depending on site/implementation?)
#### client/api interaction
- when a user accepts a task, the backend should be updated with the assignment
- when a task is marked complete, the backend should be updated with the status