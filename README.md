# SpringBootProj - postman-->SpringAppln-->OracleDB
Spring Boot java application - developed on eclipse with built in apache tomcat.
Has pom.xml for maven dependencies and application.properties for configuration details.
The application is connected with Oracle database.The application.properties files has oracle 11g configs.
Run the application as Java Application and invoke it from Postman tool as shown in picture attached (postman.jpgs)

Created a Tutorial Management System-All CRUDS on tutorial table.
Tutorial POJO - setters and getters,constructors.
TutorialController- maps the http requests to parts of application
TutorialRepository -implements JPARepository interface for CRUD operations.
