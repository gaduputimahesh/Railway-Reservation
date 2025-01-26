# Railway Reservation Portal

This is a Python-based Railway Reservation Portal, which allows users to book and cancel train tickets, check PNR status, and more. The system includes functionalities for user authentication, ticket management, and seat availability checking. 

### Features
1. **User Authentication**: 
   - Users can create new accounts and log in with their credentials.
   - User credentials and booking history are saved securely.

2. **Train Management**:
   - Multiple trains with seat availability for different classes (1AC, 2AC, SL) are managed.
   - Train details include train name, number, source, destination, and departure/arrival times.

3. **Ticket Management**:
   - Users can book tickets for available trains, selecting the class of service.
   - Tickets are linked to users via a unique PNR number.
   - Users can cancel tickets and check the status of previously booked tickets using their PNR number.

4. **Seat Availability**:
   - The system checks and displays seat availability in various train classes.
   - The availability is updated as users book or cancel tickets.

5. **Persistent Data**:
   - The system loads and saves data using Python's `pickle` module to ensure persistent data storage for trains, users, and tickets.

### Technologies Used

- **Python 3.x**: The programming language used for the entire project.
- **Pickle**: Python's module for serializing and deserializing data. It is used to save and load the system's data (trains, users, and tickets).
- **Object-Oriented Programming (OOP)**: The code follows an object-oriented approach with classes representing trains, users, tickets, and input validation.
  
### Requirements
- Python 3.x
- `pickle` module (comes pre-installed with Python)

### Installation

1. Clone this repository to your local machine.

2. Make sure you have Python 3.x installed.

3. Run the `railway_reservation.py` script.

### Usage

Once the script runs, the system will display a menu with various options:

1. **Book Ticket**: Allows you to book a ticket after checking the seat availability.
2. **Cancel Ticket**: Allows you to cancel a previously booked ticket using the PNR.
3. **Check PNR**: Allows you to check ticket details using the PNR.
4. **Check Seat Availability**: Lets you check the seat availability for a specific route.
5. **Create New Account**: Create a new user account for the portal.
6. **Check Previous Bookings**: Check all your past bookings.
7. **Login**: Log in to your account to access your profile and bookings.
8. **Exit**: Exit the application.

### Data Persistence

Data is saved in a `data.pkl` file, which stores:
- **Trains**: A dictionary containing all available trains and their details.
- **Users**: A dictionary containing all user profiles.
- **Tickets**: A dictionary containing all booked tickets linked with PNR numbers.

### Example:

![Screenshot (163)](https://github.com/user-attachments/assets/571b2583-0856-429c-a9c0-8bcd4225083a)


