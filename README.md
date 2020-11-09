# Reimbursement Project

Full-stack Web development project made in 2 weeks from technologies that I started off unfamiliar with. Technologies used, from backend to frontend:

- **Amazon AWS RDS**
  
  Used to host the relational database that holds user & reimbursement data.
- **PostgreSQL**
  
  Database management system and superset of SQL scripting languages. Accessed at developer-side using **DBeaver**.
- **JDBC**
  
  Java's back-end database connection and data retrieval API.
- **Maven**
  
  Project structure & dependency manager. Used to manage the local Java project.
- **Apache Tomcat**
  
  Web-server backend framework for Java projects. Uses front-facing Java Http Servlets.
- **Java Servlets**
  
  Java's built-in API for handling HTTP requests and responses. Used for routing to new pages and for returning data packets to the front-end user.
- **JUnit**
  
  Test automation software used for program-internal quality assurance.
- **Jacoco**
  
  Test automation software used to generate testing reports via JUnit.
- **Amazon AWS EC2**
  
  Virtual Linux machines hosted by the Amazon Cloud, used to provide a remote endpoint for the Web application.
- **Jenkins**
  
  Server deployment automation software. Installed onto the Amazon EC2 within its Tomcat runtime in order to build, test and deploy the Web application. I also configured a Github webhook to allow the server to automatically pull in updates whenever they are pushed to this repository.

Project was commissioned as a paid assignment by Revature, LLC.
