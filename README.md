# Quiz App:

![Quiz App Logo](https://ramin.website/assets/images/projects/quiz-app.jpg)

The Quiz App is a web application designed to entertain and educate users by offering engaging quizzes on various topics. The aim is to promote both fun and learning through interactive and enjoyable quiz experiences.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)

## Features
- Engaging quizzes on various topics.
- User-friendly interface.
- Educational content mixed with entertainment.

## Technologies Used
### Backend
- [Express](https://expressjs.com/) - Web application framework for Node.js.
- [MongoDB](https://www.mongodb.com/) - NoSQL database for storing quiz data.
- [Mongoose](https://mongoosejs.com/) - MongoDB object modeling for Node.js.
- [Node.js](https://nodejs.org/) - JavaScript runtime for server-side development.
- [Nodemon](https://nodemon.io/) - Utility to monitor for changes and restart the server.

### Frontend
- [React](https://reactjs.org/) - JavaScript library for building user interfaces.
- [Axios](https://axios-http.com/) - Promise-based HTTP client for the browser and Node.js.
- [Styled Components](https://styled-components.com/) - CSS-in-JS library for styling React components.
- [TypeScript](https://www.typescriptlang.org/) - Typed superset of JavaScript.
- [gh-pages](https://www.npmjs.com/package/gh-pages) - Publish files to a GitHub Pages branch.

## Installation
1. Clone the repository.
   ```bash
   git clone https://github.com/Rsmk-code/Quiz-App
   cd quiz-app
   ```

2. Install backend dependencies.
   ```bash
   cd backend
   npm install
   ```

3. Install frontend dependencies.
   ```bash
   cd ../frontend
   npm install
   ```

## Usage
1. Start the backend server.
   ```bash
   cd ../backend
   npm run start
   ```

2. Start the frontend application.
   ```bash
   cd ../frontend
   npm start
   ```

3. Open your browser and visit [http://localhost:3000/](http://localhost:3000/) to use the Quiz App.

## Development
- For backend development, use the `start-dev` script to run the server with nodemon.
  ```bash
  cd backend
  npm run start-dev
  ```

- For frontend development, use the `start` script to run the development server.
  ```bash
  cd frontend
  npm start
  ```
