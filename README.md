JavaFX Database Table Viewer – Parmjeet Singh
Student Name: Parmjeet Singh
Student ID: 230999
Date: Automatically displayed using system date (yyyy-MM-dd format)
Section A – Design and GUI (120 Marks)
A JavaFX application is created using Main.java.

The GUI includes:

Labels to show your name, student ID, and current date.

A TableView to display person data (First Name, Last Name, Age).

Sample data is loaded directly into the TableView using ObservableList.

Uses HBox and BorderPane layout managers for structured design.

No visual assets are included; output is rendered via JavaFX components.

Section B – Database Connection (180 Marks)
The class DatabaseConnection.java is responsible for connecting to a MySQL database.

It uses the following:

JDBC URL: jdbc:mysql://localhost:3306/your_database_name

MySQL username: your_username

MySQL password: your_password

The connection is established using DriverManager.getConnection(...) inside a try-catch block.

The class prints connection success or failure messages to the console.

Section C – Data Retrieval (240 Marks)
A Person model class is defined in person.java:

java
Copy
Edit
public class person {
    private String firstName;
    private String lastName;
    private int age;
    // Constructor and getters
}
Sample data is added manually using FXCollections.observableArrayList(...).

Data is displayed in the JavaFX TableView using PropertyValueFactory bindings.

The current version uses hardcoded sample records, but can be extended to fetch from MySQL using ResultSet.

Section D – GitHub and Documentation (360 Marks)
The full project is to be uploaded to a GitHub repository.

Repository should contain:

Source code: Main.java, DatabaseConnection.java, and person.java

This README.md file

Optional: a DOCX version of the documentation
