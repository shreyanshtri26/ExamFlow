
<div align="center">
  <h1>ExamFlow: All-In-One Exam Manager</h1>
  <p>
    A comprehensive online exam management system with a Node.js backend and a React.js frontend.
  </p>
  

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Tech Stack](#space_invader-tech-stack)
  * [Features](#dart-features)
  * [Environment Variables](#key-environment-variables)
- [Getting Started](#toolbox-getting-started)
  * [Prerequisites](#bangbang-prerequisites)
  * [Run Locally](#running-run-locally)
  * [Run with Docker](#run-with-docker)
- [To-do](#notes-to-do)
- [Contributing](#wave-contributing)
- [License](#warning-license)
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements)

<!-- About the Project -->
## :star2: About the Project
  ExamFlow is a comprehensive web application designed for managing online MCQ tests. Whether you are a student looking to take a test, a teacher wanting to create and manage questions, or an admin overseeing the entire system, ExamFlow has you covered.

<!-- TechStack -->
### :space_invader: Tech Stack

<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://reactjs.org/">React.js</a></li>
    <li><a href="https://react-redux.js.org/">React-Redux</a></li>
    <li><a href="https://www.mui.com">Material UI library</a></li>
    <li><a href="https://html.com/html5/">HTML 5</a></li>
    <li><a href="https://www.css3.com/">CSS 3</a></li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://www.nodejs.org">Node.js</a></li>
    <li><a href="https://www.expressjs.com/">Express.js</a></li>
    <li><a href="https://www.passportjs.org/">Passport.js</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mongodb.com/">MongoDB</a></li>
  </ul>
</details>


<!-- Features -->
### :dart: Features

- **Student User**
  - View Test Details
  - Register for a Test
  - Take a Test
  - Check Results with Correct Answers and Explanations

- **Teacher User**
  - Create and Update Questions and Question Banks
  - Create and View Tests

- **Admin User**
  - Create and Manage Teacher Users
  - Create and Manage Subjects

<!-- Env Variables -->
### :key: Environment Variables

To run this project, you will need to add the following variables to your `backend/config.json` file:

- `mongodb.connectionString`
- `jwt.secret`

<!-- Getting Started -->
## :toolbox: Getting Started

<!-- Prerequisites -->
### :bangbang: Prerequisites

This project uses MongoDB as a database. Please install the MongoDB server in your local environment.

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
<<<<<<< HEAD
=======
<!-- To Do -->
## :notes: to-do
  <ul>
  <li> add more features </li>
  </ul>
>>>>>>> cb59cf59beb1762dd4fbb53084c4be0f8a9660fc

<!-- Contact -->
## :handshake: Contact

Shreyansh Tripathi - [@shreyanshtri26](https://twitter.com/shreyanshtri26) - shreyanshtripathi1999@gmail.com





