# SpringMVCJDBCTemp


# Spring MVC JDBC Example

This repository contains a Spring MVC JDBC example that demonstrates CRUD (Create, Read, Update, Delete) operations. The project is built using JDK-11, Tomcat-9, and STS-4.19.

## Project Environment

- JDK: 11
- Tomcat: 9
- IDE: STS-4.19 (Spring Tool Suite)

## Project Setup

1. Clone the repository to your local machine.


3. Update the project configuration by modifying the `MvcConfiguration.java` file. Update the database URL, ID, and password to match your database configuration.

4. Run the SQL queries provided in the SQL schema file to create the necessary database tables.

## Project Structure

The project has the following structure:

- **src/main/java**: Contains the Java source code for the project.
  - **com.demo**: Root package for the project.
    - **com.demo.config**: Contains the `MvcConfiguration.java` file, which is a Java-based configuration file for the IOC (Inversion of Control) container. It handles database connectivity and redirects to appropriate views.
    - **com.demo.controller**: Contains the controller classes that handle GET and POST operations. These classes interact with the DAO class.
    - **com.demo.dao**: Contains the DAO (Data Access Object) class that implements CRUD operations such as Create, Read, Update, and Delete.
    - **com.demo.model**: Contains the model classes that represent the database entities.

- **src/main/webapp**: Contains the web application files.
  - **WEB-INF/views**: Contains the view files (.jsp files) for rendering the HTML templates. Two view files, `ContactForm.jsp` and `home.jsp`, are included in this project.

## Running the Project

1. Ensure that you have completed the project setup steps mentioned earlier.

2. Deploy the project to the Tomcat server.

3. Access the application by opening a web browser and navigating to the appropriate URL.

4. Use the provided views and forms to perform CRUD operations on the database.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


## Acknowledgements

This project utilizes the Spring MVC framework and JDBC for performing CRUD operations. We acknowledge the developers and contributors to the Spring framework for their work and support.

Feel free to download the project and modify it according to your needs. Happy coding!
