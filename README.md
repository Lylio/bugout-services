![](https://github.com/Lylio/image-repo/blob/master/logos/java.png?raw=true)
![](https://github.com/Lylio/image-repo/blob/master/logos/spring-boot.png?raw=true)
![](https://github.com/Lylio/image-repo/blob/master/logos/angular.png?raw=true)
![](https://github.com/Lylio/image-repo/blob/master/logos/postgres.png?raw=true)
# BugOut-Services
## Built with Spring Boot, Angular.js and PostgreSQL

### Description
Issue/bug tracking software. Demo can be found at http://bugout.lylio.tech

#### Database
1. Create a Postgres database called 'bugout':  
   `CREATE DATABASE bugout`
2. Create tables and insert test data by running src/main/resources/import.sql

#### Docker Launch
1. `docker build -t bugout-services .`
2. `docker run -p 8080:8080 bugout-services:latest`
3. Navigate to http://localhost:8080

#### Maven Launch
1. `mvn spring-boot:run`
2. Open browser at http://localhost:8080
