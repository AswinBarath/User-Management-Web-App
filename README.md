# CRUD User Management Application

- A MERN stack User Management Web App with CRUD operations
- **MVC** (Model-View-Controller) is an application design pattern that seperates the application data from business logic and presentation

## Project structure

- **assets** folder contains the css files, images and JavaScript files in their respective sub folders
- **server** folder contains all server side code and imitates the *MVC* (Model-View-Controller) pattern to categorize each part of the codebase
  - controller folder deals with user requests for resources from the server
  - routes to handle different routes
  - services to handle different services
  - database to manage database connections
  - model folder will work with MongoDB data, perform data validation, processing data, creating Mongo schemes
- **views** contains the HTML files and using *EJS* (Embedded JavaScript) template engine, dynamic HTML pages are created and stored here
