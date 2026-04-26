Database:
Swapped to h2 In-memory database

Acess + access settings : 
http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:taskboarddb
Username: sa
Password: (leave empty)
Click "Connect"






New Endpoints added:
GET /api/tasks/completed - get all completed task
GET /api/tasks/incomplete - get all incompleted task
GET /api/tasks/priority/HIGH - get task by priority
GET /api/tasks/search?keyword=... - search task with keywords
GET /api/tasks/paginated?page=0&size=5 - get paginated task

