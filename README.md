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
This project is simple implementation of real cinema web application with authentication

![line](src/main/resources/images/rainbow.png)

<a name="Features⚙"></a>
## Features
When you open application website you can login or register
### If you login as user with role USER, you can:
- See all information of movies, cinema halls and movies sessions
- Add a ticket to the shopping cart 
- Create order
- See order history
- Logout
### If you login as user with role ADMIN, you can:
- See all information of movies, cinema halls and movies sessions
- Create, modify and delete cinema-hall, movies, and movie sessions from the database
- Get info about user by email
- Logout

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