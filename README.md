# CINEMA APP
![pic](src/main/resources/images/cinema.jpg)
## Content
![line](src/main/resources/images/rainbow.png)

- [About The Project](#About-The-Project)
- [Features](#Features)
- [Project structure](#Project-structure)
- [Technologies](#Technologies)
- [How to run project](#How-to-run-project)

![line](src/main/resources/images/rainbow.png)

<a name="About-The-Project"></a>
## About The Project
This project is simple implementation of real cinema web application with authentication and authorization

![line](src/main/resources/images/rainbow.png)

<a name="Features⚙"></a>
## Features
This project have multiple endpoints with user and admin access.
### You can see them here:
- POST: /register - all
- GET: /cinema-halls - user/admin
- POST: /cinema-halls - admin
- GET: /movies - user/admin
- POST: /movies - admin
- GET: /movie-sessions/available - user/admin
- GET: /movie-sessions/{id} - user/admin
- POST: /movie-sessions - admin
- PUT: /movie-sessions/{id} - admin
- DELETE: /movie-sessions/{id} - admin
- GET: /orders - user
- POST: /orders/complete - user
- PUT: /shopping-carts/movie-sessions - user
- GET: /shopping-carts/by-user - user
- GET: /users/by-email - admin

![line](src/main/resources/images/rainbow.png)

<a name="Project-structure"></a>
## Project structure
Project is built on a three-tier architecture:
1. Presentation layer (controllers);
2. Application layer (service);
3. Data access layer (DAO)

![line](src/main/resources/images/rainbow.png)

<a name="Technologies"></a>
## Technologies
- Spring (Core, Web, Security)
- Hibernate 
- Apache Tomcat (v. 9.0.50)
- MySql

![line](src/main/resources/images/rainbow.png)

<a name="How-to-run-project"></a>
## How to run project
### Needfull tools:
- Intellij IDEA Ultimate
- MySql
- Apache Tomcat
1. Clone this project
2. Add new configuration TomCat Local server
3. Change username and password in db.properties
4. Create schema in MySQL
#### After running the application you can login:
- as ADMIN (username: admin@i.ua, password: 1234)
- as USER (username: user@i.ua, password: 1234)

![line](src/main/resources/images/rainbow.png)