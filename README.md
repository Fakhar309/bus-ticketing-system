****Bus Ticket Reservation System****

This C++ project implements a simple console-based bus ticket reservation system. Users can book new tickets, view booked tickets, and check available buses. Ticket details are saved to and loaded from a file for persistence.

**Features**

Book New Ticket: Users can enter passenger details, select cities, buses, and time slots to book a new ticket.
View Tickets: Display all booked tickets with detailed information.
Check Available Buses: List all buses available from each city.
File Persistence: Save and load ticket details to/from a file (tickets.txt).


**How to Use**

Run the Program: The menu provides options to book a new ticket, view booked tickets, and check available buses.
Book a Ticket: Follow prompts to enter passenger name, select cities, bus, and time slot. A seat is assigned automatically.
View Tickets: Displays all booked tickets with information like passenger name, cities, bus, driver, departure and reach times, and seat number.
Check Buses: Lists all buses available from each city.


**Code Overview
Main Functions:**
newTicket(): Handles the ticket booking process.
viewTicket(): Displays all booked tickets.
availableBuses(): Lists available buses for each city.
saveTicketToFile(): Saves ticket details to tickets.txt.
loadTicketsFromFile(): Loads ticket details from tickets.txt.


**Utilities:**
getValidatedInput(): Validates user input within a range.
displayCities(): Lists all cities.
displayTimeSlots(): Lists all time slots.
getRandomNumber(): Generates a random number within a range.
