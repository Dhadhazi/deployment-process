# Udagram for Deployment

This is a Udacity Full Stack JavaScript Developer Nanodegree program project, for the Deployment Process section. The code is not mine - but made some fixes so it works. The project main goal is tot deploy the app to AWS and setup a CI/CD pipeline with CircleCI.

Project documentation can be found in the documentation folder

Project Link: http://udagram-frontend-jsnd.s3-website-eu-west-1.amazonaws.com/home

## How to run it locally

1. Clone this repo locally into the location of your choice.
2. Make sure all dependencies are installed to your machine
3. Setup a Postgres Database, and add it to the config file in the frontend
4. Add all env variables for the backend
5. Run `npm run frontend:install` and `npm run backend:install` from the main directory
6. Run `npm start` to start the frontend and `npm run dev` to start the backend

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Environmental variables for the backend

All required variables can be found in the src/config/config.ts file.
Port is for the database port (usually 5432 for postgres)
