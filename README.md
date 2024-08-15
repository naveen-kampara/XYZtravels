# **XYZtravels**
A application for a new travel and logistics company to automate booking operations using core Java concepts and the Collection API, with no database involved.
# **Overview**
This project is a dynamic, menu-driven console application developed for a travel and logistics company. It automates the booking operations and is built using core Java concepts and the Java Collection API (List and Map). No database is involved in this project, ensuring that all operations are performed in-memory.

# **Features**
+ **Admin User Registration:** Allows new admin users to register by providing personal details such as first name, last name, mobile number, gender, email ID, and password. Backend fields like failedCount and accountStatus are also managed.
+ **Account Locking:** Automatically locks an account after five invalid login attempts to enhance security.
+ **Journey Planning:** Enables users to plan their journeys by selecting the source, destination, travel date, and the number of passengers. The application validates the details, calculates fares and confirms the booking.
+ **Rescheduling:** Offers users the ability to edit their travel date after booking, providing flexibility.
+ **Exception Handling:** Implements robust exception handling to manage runtime errors and provide user-friendly messages.
+ **System Logging:** Maintains system logs to track activities and improve debugging and understanding of the application's flow.

# **Technology Stack**
+ **Programming Language:** Java
+ **Core Concepts:** Java Collections API (List, Map)
+ **Java Version:** Java 8 (utilizing LocalDate features)
+ **Tools:** Console-based application

# **Installation and Setup**
 ```bash
 #To clone this repository
 git clone https://github.com/naveen-kampara/XYZtravels/tree/main.git

# Navigate to the project directory
cd XYZtravels

# Compile the Java files
javac src/*.java -d bin

# Run the application
java -cp bin Main
```
# **How to use**
+ **Launching the Application:** Upon starting the application, the company logo will be displayed. If the logo loads successfully, the main menu will be shown.

+ **Admin Registration:** Select the "New Admin User Registration" option and provide the necessary details.

+ **Planning a Journey:** Choose "Plan Journey" to select your source, destination, travel date, and number of passengers. The application will validate your input, calculate the fare, and confirm your booking.

+ **Rescheduling:** If you need to change your travel date, select the "Reschedule" option from the main menu.

+ **Account Locking:** If you enter the wrong login details five times, your account will be locked for security purposes.

# **Additional Features**
+ Provides the ability to display user-friendly messages for various runtime exceptions.
+ Ensures code reusability and high-quality coding practices.

# **Contributing**
Contributions are welcome! Please follow these steps:

1. Fork the repository.

2. Create a new branch (git checkout -b feature-branch-name).

3. Make your changes and commit them (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature-branch-name).
5. Open a pull request.



