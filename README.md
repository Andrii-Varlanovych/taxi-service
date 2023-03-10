# Taxi-service
A small web application for working with various taxi services. Project was written with the aim to show my skills in Java, OOP and SOLID principles, JDBC, Web.
After registration as a driver, you will be able to log in (using login and password) and :

- Create/remove a car;
- Create/remove a manufacturer;
- Create/remove a driver;
- Create connection a car with a driver;
- Display a list of cars;
- Display a list of manufacturers;
- Display a list of drivers;
- Display a list of cars by an authenticated driver.

# Configuration
- This project has 3 models : driver, manufacturer and car;
- On top of the project structure DAO layer is located with the corresponding interfaces and their implementations which have functions that sends queries to database;
- Services with which the user will work directly are located under the DAO layer;
- Each page of this web application has its own Servlet Controller and .jsp files to handle different types of requests from users.

# Technology
- Java 19;
- Apache Tomcat 9.0.71; 
- MySQL;
- JDBC;
- Javax servlet API;
- JSP;
- JSTL;
- HTML;
- Maven.

# How to run the project

- Clone this project;
- Install MySQL and run the script from src/main/resources/init_db.sql;
- Configure src/main/java/taxi/util/ConnectionUtil.java with your URL, USERNAME and PASSWORD;
- Install Tomcat 9.0.71 configure and run.


