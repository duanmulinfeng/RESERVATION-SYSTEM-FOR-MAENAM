# RESERVATION-SYSTEM-FOR-MAENAM
# Restaurant Reservation System

## What the Project Does

The **Restaurant Reservation System** is a Python-based software designed to streamline the reservation and waitlist management for restaurants. The system allows restaurant managers to handle customer reservations, manage table availability, and efficiently track waitlisted customers, ultimately improving the dining experience for both customers and staff.

## Why the Project Is Useful

This project addresses key challenges in restaurant operations, such as:
- Double bookings or overbooking issues.
- Managing customer flow during peak dining hours.
- Efficient table allocation.
- Handling reservations for special occasions or specific requirements.

By automating the process of reservation management and waitlist tracking, restaurants can avoid errors, optimize seating, and enhance customer satisfaction.

Key features of the system include:
- Easy creation of customer profiles.
- Real-time table availability checks.
- Automated handling of reservations and waitlists.
- Integration with restaurant-specific data, like hours of operation and table sizes.

## Who Will Use It

The **Restaurant Reservation System** is designed for:
- **Restaurant Managers**: To manage table reservations, customer waitlists, and customer interactions.
- **Restaurant Staff**: To access reservation information, check table availability, and assist customers with their bookings.
- **Customers**: To book reservations or join a waitlist at participating restaurants.


## Features

- **Customer Management**: Add and manage customer information.
- **Table Management**: Check table availability, reserve, and release tables.
- **Reservation System**: Create and manage reservations.
- **Waitlist**: Add customers to a waitlist when no tables are available.
- **Restaurant Management**: Manage multiple restaurants with customizable hours and tables.

## Classes

1. **Customer**: Represents a customer with details like name, phone number, and email.
2. **Table**: Handles table attributes, availability, and reservations.
3. **Reservation**: Represents a confirmed booking.
4. **Waitlist**: Inherits `Reservation` for waitlist management.
5. **Restaurant**: Manages reservations, waitlists, and tables for a restaurant.
6. **ReservationSystem**: Acts as the core manager for customers, reservations, and restaurants.
   

