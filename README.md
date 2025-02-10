Explanation for the program:

The Code uses an array of boolean values to represent the seats on the plane. 
A value of true in the array indicates that a seat is reserved, and a value of false indicates that a seat is available. 
The program has a main method part  that serves as the entry point and contains a while loop that displays a menu to the user with three options:

1. Reserve a seat
2. View all seats
3. Exit

When the user selects option 1, the program calls the reserveSeat method. 
This method prompts the user to enter a seat number and then checks if the seat is available (i.e. the corresponding value in the seats array is false). 
If the seat is available, the program reserves the seat by setting the corresponding value in the seats array to true, and displays a message to the customers. 
If the seat is not available, the program displays a message to the user indicating that the seat is already reserved.

If the user selects option 2, the program calls the viewSeats method. 
This method loops through the seats array and displays the status of each seat (i.e., whether it is available or reserved) to the user.

Finally,  if the user selects option 3, the program exits the while loop, and the program ends.

While this example is a simple and Easy to use, it demonstrates how an airline reservation system can be implemented using Java. 
However, it’s important to note that this is not a complete solution, it doesn’t cover all the features that a complete Airline Reservation System would have, such as authentication, booking history, flight schedule, payment gateway integration, etc. 
It also doesn’t include error handling, data validation and other important features that would be included in a production ready system. 
But it is a good starting point for those who are interested in understanding how the basic functionality of an airline reservation system can be implemented in Java.

