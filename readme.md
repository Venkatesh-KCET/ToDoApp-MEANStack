# ToDoApp-MEANStack

![logo](./angular-src/src/icon.png)

A simple to-do list application with accounts and authentication to store a to-do list for each user using MEAN stack technologies.

[![GitHub License](https://img.shields.io/github/license/Etshawy1/ToDoApp-MEANStack?style=plastic)](https://img.shields.io/github/license/Etshawy1/ToDoApp-MEANStack?style=plastic)
[![GitHub contributors](https://img.shields.io/github/contributors/Etshawy1/ToDoApp-MEANStack?style=plastic)](https://img.shields.io/github/contributors/Etshawy1/ToDoApp-MEANStack?style=plastic)
[![GitHub stars](https://img.shields.io/github/stars/Etshawy1/ToDoApp-MEANStack?style=plastic)](https://github.com/Etshawy1/ToDoApp-MEANStack/stargazers?style=plastic)

## Tools Used

- **Server:** [Node.js](https://nodejs.org/en/download/) with [Express](https://expressjs.com/) as the framework.
- **Frontend:** [Angular](https://angular.io/)
- **Database:** [MongoDB](https://www.mongodb.com/)
- **Function Documentation:** [JSDoc](https://jsdoc.app/)
- **API Documentation:** [Postman](https://documenter.getpostman.com/view/10629897/SzzoZFE8)
- **Code Style:** [Airbnb](https://github.com/airbnb/javascript)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

#### Back-end

1. Clone the project repository, then open a terminal in the root directory and run the following command to install dependencies:

   ```bash
   npm i
   ```

2. Create a file named `.env` in the root directory (use the `example.env` as a reference for required environment variables).

3. Switch to Node.js version 10.24.1 using `nvm`:

   ```bash
   nvm install 10.24.1
   nvm use 10.24.1
   ```

4. Install `nodemon` globally to enable automatic server refresh on file changes:

   ```bash
   npm i -g nodemon
   ```

5. Run the backend using:

   ```bash
   nodemon
   ```

#### Front-end

1. This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.9.

2. To install Angular CLI globally, run:

   ```bash
   npm i -g @angular/cli@9.1.9
   ```

3. Navigate to the `./angular-src` directory and build the project:

   ```bash
   ng build
   ```

   The build artifacts will be stored in the `./public` directory. Use the `--prod` flag for a production build.

4. To run the frontend with OpenSSL support, use:

   ```bash
   node --openssl-legacy-provider ./node_modules/@angular/cli/bin/ng serve
   ```

### API Documentation

The Postman documentation was used for this project. You can find the Postman collection in the root of the repository in JSON format, which can be imported into the Postman application. You can find the online documentation [here](https://documenter.getpostman.com/view/10629897/SzzoZFE8).

## Screenshots

![home](./screenshots/home.PNG)

![register](./screenshots/signup.PNG)

![login](./screenshots/login.PNG)

![TODOLIST](./screenshots/list.PNG)

## Author

- [Muhammad Ahmad Hesham](https://github.com/Etshawy1)

## License

- Licensed under the [MIT License](./License).

## External Links

You can find a Heroku-deployed version of the project at the following [link](https://task-organizer-mean.herokuapp.com/).