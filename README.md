# CRUD - User API with Java and Spring Boot
This project is a REST API for managing products, built with Java 17, Spring Boot 3, and H2. The API allows you to create, read, update, and delete users.

### How to Run?
1. Open the project in your IDE (recommended: IntelliJ IDEA).

2. Download the dependencies:
Maven will handle this automatically once the project is loaded.

3. Configure your database:

- Open the application.properties file
- Check if you want to change anything.

<img width="552" height="385" alt="BD - 1" src="https://github.com/user-attachments/assets/07e11b39-68db-446f-99da-91572ff798a0" />


4. Run the application:

- Execute the CadastroUsuarioApplication main class.
- The API will be available at: http://localhost:8080

### Requirements:

 . Java 17
 . Maven


### API Features
Base URL: http://localhost:8080

#### saveUser -> POST /usuario
 ### REQUEST

<img width="854" height="413" alt="post" src="https://github.com/user-attachments/assets/16a4c42a-6d15-4ef5-b73b-7495653e5ce0" />

<img width="533" height="271" alt="BD - 2" src="https://github.com/user-attachments/assets/bb4a9745-cd01-434a-bc60-9ee40d16da3d" />


#### getByEmail -> GET /usuario

<img width="839" height="478" alt="GetByEmail" src="https://github.com/user-attachments/assets/b0addc94-91b2-4d23-9146-0af54bb5f488" />


#### update -> PUT /usuario

<img width="853" height="414" alt="update" src="https://github.com/user-attachments/assets/f629b615-031f-41a2-840a-6372740e681d" />

<img width="345" height="130" alt="update - data" src="https://github.com/user-attachments/assets/b3eaed37-fd93-4b2b-bd6d-068c5477db3a" />


#### delete -> DELETE /usuario

<img width="839" height="398" alt="1- post to delete" src="https://github.com/user-attachments/assets/7d8eaf8d-fed0-4a23-be5b-41e1f808d10f" />

<img width="394" height="124" alt="1 1 - see data" src="https://github.com/user-attachments/assets/5422f02f-980f-455d-9e81-89626876a0a3" />

<img width="837" height="387" alt="1 2 - delete" src="https://github.com/user-attachments/assets/fb7d80f2-5773-4799-9307-58f311aeb258" />


## Stacks
- Java 17
- Spring Boot 3
- Spring Data JPA
- H2
- Maven

# Tools
- macOS
- IntelliJ IDE
- Postman

Developed by [Leandro Ucuamba](https://www.linkedin.com/in/leandrosantosucuamba/)

