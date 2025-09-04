Showroom Management System
A simple Java Swing-based desktop application for managing car showrooms, employees, and car inventory. This application provides a graphical user interface (GUI) to easily add and view information.

📝 Description
This project is a GUI version of a console-based showroom management system. It allows users to perform basic Create and Read operations for three main entities: Showrooms, Employees, and Cars. The application features separate panels for each action, providing a user-friendly experience. The main menu features a dynamic background image for a more polished look.

✨ Features
Add Showrooms: Add a new showroom with details like name, address, manager, and number of employees.

View Showrooms: Display a list of all added showrooms.

Add Employees: Add a new employee with their name, age, department, and associated showroom.

View Employees: Display a list of all employees.

Add Cars: Add a new car with its name, color, fuel type, price, and other specifications.

View Cars: Display a list of all cars in the inventory.

User-Friendly Interface: A multi-panel interface built with Java Swing for easy navigation.

Dynamic Data Storage: Uses ArrayList to store data, allowing for an unlimited number of entries.

📂 Project Structure
The project is organized into five .java files, all located in the same directory:

File

Description

MainGUI.java

The main entry point of the application. It creates the main window, manages all GUI panels, and handles user interactions.

Utility.java

An interface that defines a common get_details() method, ensuring all data classes can be displayed consistently.

Showroom.java

A class that represents a showroom, holding all its relevant details.

Employees.java

A class that represents an employee, linked to a specific showroom.

Cars.java

A class that represents a car, containing its specifications.

🚀 How to Run
To compile and run this project, you need to have a Java Development Kit (JDK) installed on your system.

Save all Files: Place all five .java files (MainGUI.java, Utility.java, Showroom.java, Employees.java, Cars.java) in the same folder.

Open a Terminal/Command Prompt: Navigate to the directory where you saved the files.

cd path/to/YourProjectFolder

Compile the Code: Compile all the .java files. The *.java wildcard will compile all files in the directory.

javac *.java

Run the Application: Run the main class MainGUI to launch the application.

java MainGUI

🛠️ Technologies Used
Language: Java

GUI Framework: Java Swing
