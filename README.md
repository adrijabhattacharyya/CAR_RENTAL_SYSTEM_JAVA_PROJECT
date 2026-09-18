1. Project Title :

   Car Rental System

   This is a Java-based console application designed to manage car rentals, customer details, rental transactions, and car availability.

2. Overview of the Project :

    The Car Rental System is a menu-driven Java application that provides a simple way to manage the basic operations of a car rental service. This system
    allows users to view available cars, rent a car, enter customer details, specify the rental duration, calculate the total rental cost, and return rented
    cars. The project is developed using Object-Oriented Programming (OOP) concepts in Java. Different classes are used to represent cars, customers,
    rental transactions, and the overall rental management system. This project maintains the availability status of each car. When a car is rented, its status        changes to unavailable, and when it is returned, the status changes back to available.

 3. Features :

    The main features of the Car Rental System are:

       a) View Available Cars – Displays cars that are currently available for rental.
    
       b) Rent a Car – Allows the customer to select a car using its Car ID.
    
       c) Customer Registration – Stores the customer's name and generates a unique customer ID.
    
       d) Rental Duration – Allows the user to specify the number of days for which the car is required.
    
       e) Automatic Price Calculation – Calculates the total rental cost based on the daily rental price and number of rental days.
    
       f) Rental Confirmation – Allows the customer to confirm or cancel a rental before completing the transaction.
    
       g) Return a Car– Allows users to return a rented vehicle.
    
       h) Car Availability Management – Automatically updates the availability status of cars.
    
       i) Rental Tracking – Maintains information about active rental transactions.
    
       j) Input Validation – Checks for invalid car selections, unavailable cars, invalid menu choices, and invalid rental durations.
    
       k) Menu-Driven Interface – Provides a simple console-based interface for interacting with the system.


 4. Technologies / Tools Used :

     Programming Language :
    
                  Java

     Java Concepts Used :

                  Object-Oriented Programming (OOP)
    
                  Classes and Objects
    
                  Encapsulation
    
                  Constructors
    
                  Methods
    
                  Conditional Statements
    
                  Loops
    
                  ArrayList / List
    
                  Exception-free input handling using Scanner

      Java Libraries Used :

                  java.util.ArrayList
    
                  java.util.List
    
                  java.util.Scanner

      Development Tools :

                  The project can be developed and executed using any Java-compatible IDE or online compiler, such as:

                        a) IntelliJ IDEA
    
                        b) Eclipse
    
                        c) NetBeans
    
                        d) Visual Studio Code
    
                        e) OnlineGDB
    
                        f) Command Prompt / Terminal with JDK

      Requirements :

                  Java Development Kit (JDK) 8 or above


5. Steps to Install & Run the Project :

     Step 1: Install Java :

         Install the Java Development Kit (JDK) on your computer.
   
         Verify the installation by opening Command Prompt and running:
   
         java -version

     Step 2: Download or Clone the Project :

         Download the project source code or clone the project repository to your computer.

     Step 3: Open the Project :

         Open the project in a Java IDE such as IntelliJ IDEA, Eclipse, NetBeans, or Visual Studio Code.

     Step 4: Save the Source File :

         Save the code in a file named Main.java. The file contains the Main class along with the other required classes.

     Step 5: Compile the Program :

         Open the terminal in the project directory and run on : javac Main.java

     Step 6: Run the Program :

         After successful compilation, run : java Main
   
         The Car Rental System menu will then appear in the console or the display screen.


6. Instructions for Testing :

      The following test cases can be used to verify that the system is working correctly.

            Test Case 1: Display Available Cars :

                  1. Run the program.
   
                  2. Select option '1' – Rent a Car.
   
                  3. Check the list of available cars.

                   Expected result:

                        C001 - Toyota Camry
   
                        C002 - Honda Accord
   
                        C003 - Mahindra Thar
 
                   All three cars should initially be displayed as available.

             Test Case 2: Rent a Car :

                   1. Select option '1'.
   
                   2. Enter a valid Car ID, for example: C003
   
                   3. Enter the customer's name.
   
                   4. Enter the number of rental days, for example: 12
   
                   5. Confirm the rental by entering: Y

                   Expected result:

                         Car rented successfully!

                   For example : For the Mahindra Thar with a rental price of $150 per day for 12 days:
   
                                 Total Price: $1800.00
   
                   The car should now be marked as unavailable.

             Test Case 3: Try to Rent an Already Rented Car :

                   1. Select option '1' again.
   
                   2. Enter the Car ID of the car that was already rented.

                   Expected result:

                         Invalid car selection or car is not available.
   
                   The system should not allow the same car to be rented again while it is already rented.

             Test Case 4: Return a Car :

                  1. Select option '2' – Return a Car.
   
                  2. Enter the Car ID of a currently rented car, for example: C003

                  Expected result:

                         Car returned successfully!
   
                  The car should become available again.

             Test Case 5: Invalid Car ID :

                  Enter a Car ID that does not exist, such as: C999

                  Expected result:

                         Invalid car selection or car is not currently rented.
                                              or
                         the corresponding invalid-selection message depending on the selected operation.

            Test Case 6: Invalid Rental Duration :

                 Try entering: 0 or a negative number of days.

                 Expected result:

                         Rental days must be greater than 0.

                 The rental should not be completed.

           Test Case 7: Exit the Program

                Select option: 3

                Expected result:

                        Thank you for using the Car Rental System!

                The program should terminate successfully.


7. Conclusion :

The 'Car Rental System' project in Java provides a simple console-based solution for managing cars and rental transactions. It demonstrates the practical 

application of Object-Oriented Programming(OOP) concepts such as classes, objects, encapsulation, collections, methods, loops, and conditional statements. 

This project can also be extended in the future by adding features such as login authentication, database connectivity, payment processing, rental history, 

and a graphical user interface(GUI).
