'Car Rental System' Project in Java :

1. Problem Statement :

   Managing car rentals manually can be very time-consuming and may lead to errors in maintaining vehicle availability, customer information, rental duration,
   and rental costs. A simple digital system is therefore required to manage these basic rental operations efficiently.The "Car Rental System" is a Java-based 
   console application developed to simplify the process of renting and returning cars. This system allows users to select an available car, enter customer
   details, specify the rental duration, calculate the total rental cost, confirm the rental, and return the vehicle. Thus , this project developed using java
   maintains the availability status of cars and tracks active rental transactions, providing a structured and organized approach to basic car rental management.


2. Scope of the Project :

   The scope of this project includes the basic operations required for managing a small-scale car rental service.

   The system covers:

      a) Managing a list of available cars.
   
      b) Storing basic car information such as Car ID, brand, model, and rental price.
   
      c) Registering customer information.
   
      d) Renting available cars.
   
      e) Recording the rental duration.
   
      f) Automatically calculating rental costs.
   
      g) Confirming or cancelling rental transactions.
   
      h) Returning rented cars.
   
      i) Updating car availability after rental and return.
   
      j) Maintaining active rental records.
   
      k) Validating basic user inputs.

  This project is designed as a console-based application and does not include advanced features such as online payment, database connectivity, 
  user authentication, or a graphical user interface(GUI).


3. Target Users :

   This system is intended for users who need to perform or manage basic car rental operations.

   A) Primary Target Users :

      i) Car Rental Staff – To manage available vehicles, rental transactions, and returned cars.
   
      ii) Customers – To select cars, provide their details, choose rental duration, and rent or return vehicles.

   B) Secondary Target Users :

      i) Students and Learners – This project can be used as an educational example for understanding Java and Object-Oriented Programming(OOP) concepts.
      ii) Small Rental Businesses – This basic system can serve as a starting point for developing a more advanced car rental management application.


 4. High-Level Features :

   The major features of the system are:

   1. Car Management :

      The system maintains proper information about cars, including their unique ID, brand, model, rental price per day, and availability status.

   2. Customer Management :

      Customer details are recorded and a unique customer ID is generated for each new customer.

   3. Car Rental :

      Users can select an available car using its Car ID and specify the required rental duration.

   4. Price Calculation :

      The system automatically calculates the total rental price using the daily rental rate and number of rental days. The formula to calculate is :
      
      Total Rental Cost = Daily Rental Price * Number of Rental Days

   5. Rental Confirmation :

      Before completing a rental, the system displays the rental details and allows the user to confirm or cancel the transaction.

   6. Car Return :

      Users can return a currently rented car just by entering its Car ID.

   7. Availability Tracking :

     The availability status of each car is automatically updated when a car is rented or returned.

   8. Rental Tracking : 

     The system maintains active rental records containing the selected car, customer, and rental duration.

   9. Input Validation :

     The system handles invalid car IDs, unavailable cars, invalid rental durations, and invalid menu choices.

  10. Menu-Driven Interface :

     This menu driven application provides a simple console menu through which users can choose to rent a car, return a car, or exit the system.
