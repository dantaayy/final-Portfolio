# Backend-authorization-project
This project ensures that the data that is within the database is secure and drives least privelege for all users. Non admins have limited access while admins have elevated access to view the data.
I was inspired to create this project becasue security is the most important aspect when dealing with personal information and sensitive data.

## Overview
This project is the first of mine using secure practices to ensure users do not have access to private information. Tokens are used to authenticate users to check
if a user has admin capabilities.
The specifics of this project include the following:

* Create a database of users using Sequelize

  ![image](https://github.com/dantaayy/final-Portfolio/assets/74522928/69b0d1ef-be4b-4cac-b4f3-4ddf73d8a323)

  
* JWT to manage secrets and tokens

  ![image](https://github.com/dantaayy/final-Portfolio/assets/74522928/4c381926-cb00-48b8-85ac-ccf4b0eac6b6)


* Middleware for authorization

  ![image](https://github.com/dantaayy/final-Portfolio/assets/74522928/381e094b-56f4-467c-95ee-bd10c5da9b61)

  
* API endpoints that utilize CRUD (Create, Read, Update, Delete)

  (Get your info by id - Admins can also get any user by id)

  ![image](https://github.com/dantaayy/final-Portfolio/assets/74522928/1234948c-adbc-46e8-829a-ade3680d957a)

  (Get of all users as an admin)

  ![image](https://github.com/dantaayy/final-Portfolio/assets/74522928/2a8cb2da-a733-4a8d-a4fa-45eb587a3142)

  (Delete self only - or if admin you can delete anyone as neccessary)

  ![image](https://github.com/dantaayy/final-Portfolio/assets/74522928/b26ec99e-a6e9-4927-a2f5-86d7477d4239)


### Job Functions
| Job Function   | Description    |
| -------------- | -------------- |
| 3.3   | Link code to data sets. |
| 3.7   | Can implement authentication and authorization to an API |
| 4.1   | Organizational policies and procedures relating to the tasks being undertaken, and when to follow them. For example, the storage and treatment of GDPR sensitive data. |
| 4.2   | Acts with integrity with respect to ethical, legal and regulatory ensuring the protection of personal data, safety and security. |
| 4.4   | Interpret and implement a given design whist remaining compliant with security and maintainability requirements. |
| 5.4   | Software design approaches and patterns, to identify reusable off-the-shelf solutions to commonly occurring problems. |
| 5.8   | Shows initiative and takes responsibility for solving problems within their own remit, being resourceful when faced with a problem to solve. |
| 6.4   | Communicate software solutions and ideas to technical and non-technical stakeholders. |
