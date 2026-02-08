# Train Booking System CLI

A Command Line Interface (CLI) based Train Booking System built with Java. This application allows users to sign up, login, search for trains, book seats, and cancel bookings.

##Features

-   **User Authentication**: Secure sign-up and login functionality with password hashing (BCrypt).
-   **Search Trains**: Find available trains between source and destination stations.
-   **Seat Booking**: View seat availability and book specific seats on selected trains.
-   **Booking Management**: View your booked tickets and cancel existing bookings.
-   **Data Persistence**: User and train data are stored locally in JSON files.

## Tech Stack : Java, Gradle, BCrypt

## Project Structure

-   `app/src/main/java/ticket/booking/App.java`: Main entry point of the application.
-   `app/src/main/java/ticket/booking/service/`: Business logic for User and Train services.
-   `app/src/main/java/ticket/booking/entities/`: Data models (User, Train, Ticket).
-   `app/src/main/java/ticket/booking/localDb/`: JSON files for storing data.

### Menu Options
Once the application starts, you will be presented with a menu:

1.  **Sign up**: Create a new account.
2.  **Login**: Access your account.
3.  **Fetch Bookings**: See all your current bookings.
4.  **Search Trains**: Enter source and destination to find trains.
5.  **Book a Seat**: Select a train and a specific seat (Row, Column) to book.
6.  **Cancel my Booking**: Cancel a booking using a Ticket ID.
7.  **Exit the App**: Close the application.
