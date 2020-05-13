## api based server side that multiple client types can interact with
- It should be able to return a list of tasks (task details?)
- send tasks to backend currently sqlite3.  future options might include mongodb, elasticsearch, mysql?  Fledge uses trello to track tasks.
- projects/tasks should have: (title, description, requirements(pre-requisites), expected completion time?, task contact, source-project)
- repeatable/ongoing tasks? maintain at backend level or provide capability to set recurring schedules?
- minimize user information stored to maximum extent possible