# sign-in

> CSC 583 Exam Project:
The `sign-in` application is a simple front-end application that runs on a mobile device, e.g., an iPad or an Android tablet that communicated with a back-end database.  This application is used as a kiosk device to collect information on visitors for a corporation.
	

## Non-functional Requirements

- I evaluate this project on the basis of non-functional requirements such as skills, features, constraints, usability, support, security and complexity.
- Vue is less complex, easy to implement, quick, very flexible with rich libraries.
- MEVN stack is highly portable and highly scalable. Javascript is a familiar language that offers great flexibility in terms of its applications and there exists a rich community full of support.


## Installation Instructions

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# connect with database
sudo service mongod start

```

## Architecture Discussion

This app implemets a MEVN architecture:
- MongoDB
  - MongoDB is a database program that uses JSON-like documents with schemas.
- ExpressJS
  - ExpressJS provides a set of API endpoints that makes it easy and quick to CRUD the data.
- VueJS
  - VueJS is a web application framework capable of powering advanced single-page applications(SPA). It is easy to integration into projects that use other JavaScript libraries with Vue.
- NodeJS
  - NodeJS is the runtime environment used to run the application.