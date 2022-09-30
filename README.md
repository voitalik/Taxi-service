# Taxi-service
Implement a simple taxi service that allows for the management of cars, drivers, and manufacturers.

* implemented authentication and authorization for drivers
* register new driver
* add/show cars and related drivers
* delete car
* add/show drivers and related cars
* delete driver
* add/show manufactures
* delete manufacturer

The project uses Java Servlet and JSP for processing requests from clients.
Tomcat Server is used as a servlet container.
Data storage is relational database MySQL. Access to the database is implemented by JDBC technology.

Instruction to compile and launch the application.
1. Set up database structure. You can execute SQL script src/main/resources/init_db.sql in any admin panel of your MySQL.
2. Setup connection attributes to your database into ConnectionUtil class.
3. Configure Tomcat server: add artifact for deploying.
4. Run Tomcat configuration.

You can test the application at the next address https://arcane-taiga-63211.herokuapp.com
