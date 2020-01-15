# springboot-crud-demo

Spring Boot CRUD demo is demonstration of simple CRUD operations using Spring Boot framework.

## What's inside 
This project is based on the [Spring Boot](http://projects.spring.io/spring-boot/) and uses these packages :
- Maven
- Spring Core
- Spring JPA 
- Spring MVC 
- [Thymleaf](https://thymeleaf.org)

## Database configuration 
Create a MySQL database and add the credentials to `/resources/application.properties`.

```
spring.datasource.url=jdbc:mysql://<MYSQL_HOST>:<MYSQL_PORT/<MYSQL_DATABASE_NAME>
spring.datasource.username=<USER_NAME>
spring.datasource.password=<PASSWORD>
spring.jpa.hibernate.ddl-auto=update
```
The schema of the database is also provided in the source. 
