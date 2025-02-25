Car Rental System

Overview

The Car Rental System is a simple Java-based console application that allows users to rent and return cars. It keeps track of available cars, customers, and rental transactions.

Features

Add cars to the system

Rent a car by providing customer details

Return a rented car

Calculate total rental price based on the number of rental days

Interactive menu for user input

Technologies Used

Java

Object-Oriented Programming (OOP) principles

Data structures (ArrayList)

Console-based input/output

How to Run

Clone the repository:

git clone https://github.com/yourusername/Car-Rental-System.git

Navigate to the project directory:

cd Car-Rental-System

Compile the Java files:

javac App.java

Run the application:

java App

Classes & Functionality

1. Car Class

Represents a car with attributes such as carId, brand, model, basePricePerDay, and availability.

Methods: calculatePrice(), rent(), returnCar(), and getters.

2. Customer Class

Represents a customer with attributes such as customerId, name, and number.

3. Rental Class

Represents a rental transaction with attributes: Car, Customer, and days.

4. CarRentalSystem Class

Manages the cars, customers, and rentals using ArrayList.

Provides methods to add cars/customers, rent and return cars.

Implements a user-friendly interactive menu for rental operations.

5. App Class

The entry point of the application.

Initializes the CarRentalSystem, adds sample cars, and starts the menu-driven interface.

Example Usage

===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==
Enter your name: John Doe
Available Cars:
C001 - Toyota Camry
C002 - Honda Accord

Enter the car ID you want to rent: C001
Enter the number of days for rental: 3

== Rental Information ==
Customer ID: CUS1
Customer Name: John Doe
Car: Toyota Camry
Rental Days: 3
Total Price: $180.00

Confirm rental (Y/N): Y
Car rented successfully.

Future Improvements

Implement database storage for persistent data

Add GUI interface for a better user experience

Implement online booking system with payment integration

Contributing

Feel free to fork this repository and contribute by submitting pull requests. Suggestions and improvements are welcome!

License

This project is open-source and available under the MIT License.

Made with ❤️ by [Ayan sarakar]

