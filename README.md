# Login-Signup Mini Application
This is a simple login and signup application that can be used in bigger projects where user authentication is required.

## Getting Started
Clone the entire folder on your PC to start using this application.

## Prerequisites
NodeJS needs to be installed on the host system. Visit https://nodejs.org/en/ for downloading setup.

## Setup
Using the command line navigate to the backend directory in this project on your pc. Type npm install on your command line and hit enter. The required packages will be downloaded.


## Running and Testing
The frontend and backend runs separately. The port used for backend is 3000. You can change it in the server.js file if you want. 
- For the frontend open the index.html file in your broswer.
- For backend navigate to backend folder inside the project using command line. Type npm start and hit enter. The backend server will start.
- There are currently only two routes in the API. They are register and login for their respective purposes. Both of these are post requests.

## Built With
- NodeJS - For the backend
- Jquery, HTML, CSS - For the frontend 
- MongoDB - For the database

## API Documentation
- Register : A sample request would be like 
```
{
   "email": "your_email",
   "name": "your_name",
   "password": "your_password",
   "dob": "your_dateOfBirth"
}
```
- Login : A sample request would be like
```
{
   "email": "your_email",
   "password": "your_password"
}
```
## Frontend Screens
![Home Page](https://github.com/adityajha1707/login-signup-nodejs-mongodb/blob/master/frontend%20screens/home.png)
-![Login Page](https://github.com/adityajha1707/login-signup-nodejs-mongodb/blob/master/frontend%20screens/login.png)
-![Register Page](https://github.com/adityajha1707/login-signup-nodejs-mongodb/blob/master/frontend%20screens/register.png)
-![Success Page](https://github.com/adityajha1707/login-signup-nodejs-mongodb/blob/master/frontend%20screens/success.png)
