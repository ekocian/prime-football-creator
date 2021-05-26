# prime-futball-creator (PFC)
A simple football team manager

This project is aim to demostrate different techonologies used regulary with Javascript. In that sense a very simple backend will be built with Typescript, able to handle the bussines logic of a football team manager.

This will cover the following features:

- User authentication/authorization (admin and clients profiles)
- CRUD for Players
- Team creator
- Statistics (Players and Matches)

## Tech stack used
- Docker as container engine and docker-compose as orchestrator
- Typescript as main backend language
- Express as router framework
- Passport as authentication framework
- MongoDB as DB system with mongoose as object modeling
- Jest as testing library

# How to run locally
```
git clone 
cd prime-futball-creator
docker-compose up -d
```
And go to localhost:8080/api/v1/health-check. you should get a valid timestamp in your browser

# How to run test
Once in the project folder
```
npm run test
```
