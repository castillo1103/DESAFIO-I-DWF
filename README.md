# DESAFIO I
<h2> 
🤝Members:
  
Caleb Alejandro Peñate Deras PD230166
  
Camila Elizabeth Castillo Joya CJ220498
</h2>

✏️<b>Description:</b>

This project is a RESTful API developed with Spring Boot and JPA that allows you to manage a book catalog. Each book includes information such as title, author, and year of publication. The application performs basic CRUD operations (create, read, update, and delete books) on an in-memory H2 database. It is structured following good development practices, such as the use of REST controllers, repositories, and proper error handling. It can also be easily tested using tools like Postman, without the need for a graphical interface. It is ideal for educational purposes or as a basis for more complex projects.

🔧<b>​Technologies Used</b>

-Java 17+

-Spring Boot

-Spring Data JPA

-H2 Database

-Postman (for endpoint testing)

🚀​<b>How to execute the project?</b>

1.Clone the repository:

-Open a terminal or console.

-Navigate to the folder where you want to save the project.

-Run the command:

git clone https://github.com/castillo1103/DESAFIO-I-DWF

2.Open the project in IntelliJ IDEA
   
-Open IntelliJ IDEA.

-Select File > Open.

-Locate and select the project's root folder (where the pom.xml file is located).

-Wait for IntelliJ to import the project automatically (you'll see Maven download and compile).

-If it doesn't configure automatically, make sure you have the Java 17 SDK configured:

Go to File > Project Structure > Project > Project SDK and select Java 17.

3.Run the application

-Right-click the main class (Application.java) and select Run.

-And ready, the project is now running

🗄️​<b>Access the H2 console</b>

-In your preferred browser, enter the following address:

http://localhost:8081/h2-console

-Put the URL of the project that is in the application.propities

  JDBC URL: jdbc:h2:mem:booksdb

📮 Test the API with Postman

-You can use Postman to test each of the API endpoints.

  ✔️​GET http://localhost:8081/api/books → List all books

  ✔️​GET http://localhost:8081/api/books/{id} → Display a book by ID

  ✔️​POST http://localhost:8081/api/books → Create a new book

  ✔️​PUT http://localhost:8081/api/books/{id} → Update a book

  ✔️​DELETE http://localhost:8081/api/books/{id} → Delete a book

