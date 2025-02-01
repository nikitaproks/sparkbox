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
- [X] Create a new project
- [X] Setup minimal FastAPI project
- [X] Create docker and docker-compose files
- [ ] Setup ORM
- [ ] Setup Alembic
- [ ] Add FastApi Users lib and Create User model
- [ ] Create Request model
- [ ] Add CRUD for Users
- [ ] Add CRUD for Requests
