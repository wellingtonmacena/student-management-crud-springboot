# **CRUD Spring Boot Project**  

![status](https://img.shields.io/badge/STATUS-COMPLETED-green)  

## **About the Project**  

A web application modeled following the MVC pattern in Java and built with Spring Boot. The project includes a CRUD structure, where data is persisted in a database (MySQL). The frontend was developed using HTML, CSS, Bootstrap framework, and Thymeleaf template engine. JavaScript was also used for business rule validation.  

The system includes additional features such as a login/registration screen, user data encryption, and more.  

## **Technologies Used**  

- Java  
- Spring Boot  
- JPA / Hibernate  
- Maven  
- HTML / CSS / JS  
- Bootstrap  
- MySQL  

## **Demonstration**  

![demo](https://user-images.githubusercontent.com/89096854/170026187-57aa04f4-189b-4c00-8cc8-16a1227a5eb7.gif)  

### **Registration Form**  
![registration form](https://user-images.githubusercontent.com/89096854/170031976-645e9bd8-eaca-4a84-805c-588100e1a770.PNG)  

### **Student List**  
![student list](https://user-images.githubusercontent.com/89096854/170031981-68cf5454-a727-467c-82e6-1ba2f53c2900.PNG)  

## **Database**  

### **Student Entity**  
![student entity](https://user-images.githubusercontent.com/89096854/170030916-5c05c8c3-71d7-432e-aa6c-02b0ccf30409.PNG)  

### **User Entity**  
![user entity](https://user-images.githubusercontent.com/89096854/170030921-8948e471-b0c1-4fcc-94aa-4bc94a554df9.PNG)  

## **Installation**  

The project is managed using Maven, so to use it, simply import it into an IDE.  

## **Database Configuration**  

You can create a MySQL database with a name of your choice, but you must adjust the project settings accordingly.  

To do this, open the `application.properties` file located in `src/main/resources/application.properties` and modify the following lines:  

```properties
spring.datasource.url = jdbc:mysql://localhost:3306/your-database-name?useTimezone=true&serverTimezone=UTC
spring.datasource.username = root
spring.datasource.password = root
```

## **Execution**  

Run the project through your IDE, open a web browser of your choice, and go to:  
[http://localhost:8080](http://localhost:8080)