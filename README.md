# Travel Management System

## Angular, Node, and MySQL

1. Navigate to backend/config/config.json and change the password to your MySQL password.

```json
{
  "host": "localhost",
  "user": "root",
  "database": "posts",
  "password": "password"
}
```
Create the database tables below and refer to the main branch for the latest demo.

Note: For development purposes the host is localhost but this will need to be updated if you decide to deploy the application. By Default, MySQL gives the user 'root' with all privileges. You can simply change this to another user if desired. In this application we named our database 'posts', however, if you went with a different name this will need to be changed.

2. cd backend
3. \$ npm start
4. cd ../frontend
5. \$ npm start

# MySQL Tables
![usersTable](https://user-images.githubusercontent.com/102680541/161402943-3581d00b-0fde-4fc3-9c89-f0940a5a11b0.jpg)

![postsTablep2](https://user-images.githubusercontent.com/102680541/162085560-1b8b0b63-73ca-4081-b81e-48e7e70e4503.jpg)

## Executive Summary

The Travel Management System is the most secure system available.

Individuals with a profile may place a travel request and select and view destinations.

## User Stories

View destinations

New users and requests persist to the database

Logged in user can create a travel request

Login

Logout

Sign up/register

Select a destination from Tavel Page


## Technical Requirements

The back-end system shall use JDBC connect to an AWS RDS or MySQL database.

The application can be deployed onto a Tomcat Server using Spring Tools.

Bootstrap and components are utilized to create a dynamic Web SPA.

The front-end view shall use Angular/HTML.

The middle tier shall follow proper layered architecture, have reasonable test coverage of the service layer, and implement log4j for appropriate logging.

## Stretch Goals: 

These will count for extra credit and are entirely optional:

Registration passwords shall be encrypted in Java and securely stored in the database.

User should receive and confirmation email.
