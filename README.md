The Railway Ticket Booking System project is a Python-based application that simulates the process of booking, viewing, and canceling tickets for a railway service. The system is designed to handle basic functionalities like managing available trains, booking tickets, canceling reservations, and displaying booking records. It provides a simple and interactive command-line interface to manage train reservations.

Project Features
1. View Available Trains:
Users can see a list of available trains, each with a unique train ID, the train name, and the number of available seats.
2. Book a Ticket:
Users can select a train from the list of available trains, provide their name, and book a ticket if there are available seats. Upon successful booking, a booking ID is generated and shown to the user.
3. Cancel a Ticket:
If a user wishes to cancel a reservation, they can input their booking ID. The system will free up the reserved seat on the selected train and remove the booking from the system.
4. View Booked Tickets:
5. Users can view all the tickets they have booked. This includes showing the booking ID, the name of the user, and the train booked.

How the System Works
1. Data Structure:
The system maintains two primary pieces of information:
Trains: A dictionary where each train has an ID, name, and number of available seats.
Bookings: A dictionary that stores the booking information. The key is the booking ID, and the value contains details like the user's name and the train they booked.

2. Menu-driven Interface:
The system operates using a menu-driven approach. The user is presented with options like viewing trains, booking a ticket, canceling a ticket, or viewing booked tickets.

3. Booking and Cancellation Logic:
Booking: The system checks if there are available seats on the selected train. If available, a ticket is booked, the number of available seats is reduced, and a booking ID is generated.
Cancellation: The system checks if the provided booking ID exists. If found, the booking is canceled, the seat is freed up, and the booking information is deleted from the system.

4. User Interaction:
The system interacts with the user through the console. Users can input choices from the menu, enter their name, select a train, and even cancel their bookings.
