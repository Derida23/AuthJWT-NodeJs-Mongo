
<p align="center">
  <img width="500" height="150" src="https://blog.websecurify.com/uploads/2a3eb4a0-182a-4512-8319-87951b124a7d.png">
</p>

## Auth Express Js + Mongo Db
this project aims to study and module about simple RESTful API authentication with jsonwebtoken Express JS and Mongo database, this is a backend project to create users and enter pages that have been provided directly by the backend, and generate tokens using jsonwebtoken and bearer

<img src="https://img.shields.io/badge/express-4.17.1-blue"> <img src="https://img.shields.io/badge/bcryptjs-2.4.3-brightgreen"> <img src="https://img.shields.io/badge/dotenv-8.2.0-yellow"> <img src="https://img.shields.io/badge/jsonwebtoken-8.5.1-purple"> <img src="https://img.shields.io/badge/mongodb-3.3.5-orange"> <img src="https://img.shields.io/badge/mongoose-5.7.13-red"> <img src="https://img.shields.io/badge/validator-12.1.0-blueviolet"> <img src="https://img.shields.io/badge/env_cmd-10.0.1-violet">


### Requirement
 1. Be familiar with JavaScript ES6
 2. Basic knowledge about RESTful APIs
 3. Install Node JS and Postman
 4. Create Mongo DB and Mongo DB Atlas (to setup database) tutorial setup database and code can access in link [Frank Atukunda - Medium](https://medium.com/swlh/jwt-authentication-authorization-in-nodejs-express-mongodb-rest-apis-2019-ad14ec818122)

### Installation
1. Download zip or Git Clone https://github.com/Derida23/AuthJWT-NodeJs-Mongo.git
2. Open your code editor (vscode, atom, or another)
3. Install ``nodemon`` in global [documentation nodemon](https://www.npmjs.com/package/nodemon) 
4. Open Terminal and write ``npm install`` to install node module and packages
5. Start project with ``npm start``

### End Point
-   `HTTP POST /users`  — Register users.
-   `HTTP POST /users/login`  — Allow users to login.
-   `HTTP GET / users/me`  — Get user profile.
-   `HTTP POST /users/logout`  —Logout the user
-   `HTTP post /users/logoutall`  — Logout from all devices.

**note : to access ``HTTP GET / users/me`` me you have to copy the token that has been obtained and paste it in postman authentication with bearer token mode*
