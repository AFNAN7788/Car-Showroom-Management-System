Car Showroom Management System

Project Description

This project implements a Car Showroom Management System as a desktop application. Developed using Java Swing, it provides a user-friendly graphical interface for managing various aspects of a car showroom, including showrooms, employees, and cars. The system allows users to add new showrooms, employees, and cars, as well as view lists of all registered entities.

Features

•
Showroom Management: Add new showrooms with details such as name, address, manager, total employees, and cars in stock.

•
Employee Management: Register new employees with their name, age, department, and assigned showroom.

•
Car Management: Add new cars with specifications like name, color, fuel type, price, body type (Sedan/SUV/Hatchback), and transmission type (Automatic/Manual).

•
View Listings: Display comprehensive lists of all showrooms, employees, and cars currently in the system.

•
Intuitive GUI: Built with Java Swing for an interactive and easy-to-navigate user experience.

Technologies Used

•
Java Development Kit (JDK)

•
Java Swing for Graphical User Interface (GUI) development

•
Apache Ant (or similar build tool) for project compilation and execution (assumed based on typical Java project structure)

How to Run the Project

To set up and run the Car Showroom Management System on your local machine, follow these steps:

Prerequisites

Ensure you have the following installed:

•
Java Development Kit (JDK) 8 or higher: You can download it from the Oracle website or use a package manager like apt or brew.

Setup Instructions


1. Open the terminal and Clone the repository:

git clone https://github.com/AFNAN7788/Car-Showroom-Management-System.git


cd Car-Showroom-Management-System


2. Navigate to the project directory:
The main source code is located in the src folder.

  
3. Compile the Java source files:
Open a terminal or command prompt in the project's root directory and compile the Java files. If you are using an IDE like IntelliJ IDEA or Eclipse, it will handle compilation automatically.

Open Terminal and run:


javac -d out/production/Car\ Showroom\ Management\ System src/*.java

(Note: The out/production/Car Showroom Management System directory might need to be created manually if it doesn't exist, or adjusted based on your build setup.)



Execution

After successful compilation, you can run the application:


java -cp out/production/Car\ Showroom\ Management\ System MainGUI



Alternatively, if you are using an IDE, you can run the MainGUI.java file directly.

