# SparkBox

## Features
### Frontend
- [ ] Form to request a new ask (Title, Description, Urgency)
- [ ] Admin:
    - [ ] Settings
    - [ ] Manage Requests
    - [ ] Manage Users
### Backend
#### API:
    - [ ] Async CRUD for Users
    - [ ] Async CRUD for Requests
#### Task:
    - [ ] Huey task scheduler
    - Redis Broker backend
        - [ ] Local
        - [ ] External
    - [ ] Create Jira tickets
    - [ ] Send notifications (email)
    - [ ] Sync SparkBox with Jira
#### Authentication:
    - [ ] No authentication
    - [ ] JWT
    - [ ] Google OAuth
#### Notifications:
    - [ ] No notifications
    - [ ] Email
#### Database:
    - [ ] SQLite locally
    - [ ] Postgres externally
    - [ ] Alembic migrations
### Settings
- [ ] Choose Authentication method
- [ ] Choose Database
- [ ] Choose Notification method
- [ ] Set Jira server, credentials and project
### Deployment
- Dockerize in monolithic way
    - [ ] Dockerfile
    - [ ] Supervisor.d
    - [ ] Nginx
- CI/CD
    - [ ] Linting
    - [ ] Tests
    - [ ] Build
    - [ ] Deploy to DockerHub


## Tasks
- [ ] Create a new project
