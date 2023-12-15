
<div align="center">
  <h1>ExamFlow: All-In-One Exam Manager</h1>
  <p>
    An Online Exam portal with a Node.js backend and React.js frontend.
  </p>
  
  
<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Environment Variables](#environment-variables)
- [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Run Locally](#run-locally)
  * [Run with Docker](#run-with-docker)
- [To-do](#to-do)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

<!-- About the Project -->
## :star2: About the Project
Web Application for online MCQ test usecase

<!-- Tech Stack -->
## Tech Stack

### Frontend
- [React.js](https://reactjs.org/)
- [React-Redux](https://react-redux.js.org/)
- [Material UI library](https://www.mui.com)
- HTML 5
- CSS 3

### Backend
- [Node.js](https://www.nodejs.org)
- [Express.js](https://www.expressjs.com/)
- [Passport.js](https://www.passportjs.org/)

### Database
- [MongoDB](https://www.mongodb.com/)

<!-- Features -->
## Features

### Student User
- View Tests Details
- Register for test
- Give Test
- Check Result and correct answer and explanation for questions

### Teacher User
- Create, Update Questions and Question Banks
- Create, View Test

### Admin User
- Create and Manage Teacher users
- Create and Manage subjects

<!-- Environment Variables -->
## Environment Variables

To run this project, you will need to add the following variables to your backend/config.json file:

- `mongodb.connectionString`
- `jwt.secret`

<!-- Getting Started -->
## Getting Started

### Prerequisites

This project uses MongoDB as a database. Please install MongoDB server in the local environment.

### Run Locally

Go to the project directory

```bash
  cd project-directory
```

Install dependencies

```bash
  cd backend
  npm install
  cd ../frontend
  npm install
  cd ../user-portal-frontend
  npm install
```

Start the backend server

```bash
  cd backend
  npm start
```

Start the frontend client for admin

```bash
  cd frontend
  npm start
```

Start the frontend client for teacher/student

```bash
  cd user-portal-frontend
  npm start
```

<b>Note</b> : admin user is created when backend runs first time. default admin (username, password) details are <b>("sysadmin","systemadmin"). addAdminIfNotFound() function of backend/services/admin.js file </b> is for this logic. You can check/modify default admin details from this function.

<!-- Run with Docker -->
### Run With Docker

build docker images

```bash
  docker-compose build
```

Run container and services

```bash
  docker-compose up
```



<!-- To Do -->
## :notes: to-do
  <ul>
  <li> add more features </li>
  </ul>
 
<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/shreyanshtri26">
  <img src="https://avatars.githubusercontent.com/u/65079159?s=96&v=4" />
</a>


