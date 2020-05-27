## Cityzen server
This is a server side API that multiple client types can interact with
- It should be able to return a list of tasks (task details?)
- send tasks to backend currently sqlite3.  future options might include mongodb, elasticsearch, mysql?  Fledge uses trello to track tasks.
- projects/tasks should have: (title, description, requirements or pre-requisites, expected completion time?, task contact, source-project)
- repeatable/ongoing tasks? maintain at backend level or provide capability to set recurring schedules?
- minimize user information stored to maximum extent possible
### [User Stories](#user-stories)
- [connect to persistent storage ](server-user-stories/connect-to-persistent-storage.md) 
- [client pull a list of tasks](server-user-stories/client-pull-task-list.md)
- [mark a task accepted by a user](server-user-stories/user-accepts-task.md)
- [mark the task completed by user](server-user-stories/user-marks-task-complete.md)
- [email when a task is accepted](server-user-stories/email-when-task-accepted.md)
- [email when a task is completed](server-user-stories/email-when-task-completed.md)
- [create a user if needed](server-user-stories/create-user-if-needed-when-configured.md)
- [task not accepted if authenticated users only configured](server-user-stories/task-not-accepted-if-authenticated-only-configured.md) 
- [configurable to allow only authenticated user actions](server-user-stories/configure-authenticated-users-only.md)
- [acceptable user_id formats should be configurable](server-user-stories/configure-acceptable-user-id.md) 
- [able to create new users](server-user-stories/create-new-users.md)