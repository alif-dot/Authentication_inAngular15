# Authentication

  ============================================================================================================================
                
                Angular 15 Authentication (Registration + Login + Role based access) using JSON server REST API
                
                
![Screenshot (35)](https://github.com/alif-dot/Authentication_inAngular15/assets/62230465/8d5fe320-5aad-48af-85ec-71792c0c071e)

![Screenshot (36)](https://github.com/alif-dot/Authentication_inAngular15/assets/62230465/1a97799f-7b93-4673-ba1b-931127dcd754)

![Screenshot (37)](https://github.com/alif-dot/Authentication_inAngular15/assets/62230465/1aeb753a-227c-4c6a-853e-c899e0e586e0)

![Screenshot (38)](https://github.com/alif-dot/Authentication_inAngular15/assets/62230465/61301498-e59a-4e27-86c0-1a0f61419d79)

![Screenshot (39)](https://github.com/alif-dot/Authentication_inAngular15/assets/62230465/19122ea7-9eca-4ed8-a3b3-12fec34ef1fe)


Install Angular npm package :   npm install ng-packagr --save-dev --force
Run Json Server :   json-server --watch db.json

[ Admin id/username  - admin
Password -  alif@Idb200 ]

Angular 15 Authentication is a web application that provides user registration, login functionality, and role-based access control using Angular version 15 and a JSON server REST API. This application aims to demonstrate a secure and robust authentication system with role-based permissions for different user types.

The main features of Angular 15 Authentication include:

1. Registration: Users can sign up by providing their details such as username, email, and password. The application validates the input data and securely stores the user information in the JSON server.

2. Login: Registered users can log in using their credentials. The application verifies the entered data and authenticates the user. Upon successful login, users are granted access to restricted areas of the application based on their assigned roles.

3. Role-based Access: The application implements role-based access control, allowing different users to have different permissions based on their assigned roles. Roles such as admin, user, or guest can be defined, and specific functionalities or routes can be restricted or allowed based on these roles.

4. JSON Server REST API: The application utilizes a JSON server as a backend REST API. This server stores user data, handles authentication requests, and provides endpoints for registration, login, and role management.

5. Token-based Authentication: The authentication system uses token-based authentication for secure communication between the client and the server. Upon successful login, the server generates a unique token for the user, which is then stored on the client side. This token is sent with subsequent requests to authenticate the user and authorize access to protected resources.

6. Error Handling and Validation: The application includes robust error handling and validation mechanisms to ensure data integrity and security. It validates user input during registration and login processes, providing meaningful error messages to guide users in case of any issues.

Overall, Angular 15 Authentication provides a complete solution for user authentication and role-based access control in an Angular 15 application. It showcases best practices in building secure web applications and demonstrates the integration of Angular with a JSON server REST API to handle user registration, login, and role management.

  ============================================================================================================================

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

