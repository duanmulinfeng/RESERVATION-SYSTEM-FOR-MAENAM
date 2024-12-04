# RESERVATION-SYSTEM-FOR-MAENAM

## Restaurant Reservation System

### What the Project Does

[Maenam](https://maenam.ca/), established in 2009, is a renowned Thai restaurant in Vancouver known for its authentic, family-style Chef’s menu and carefully curated multi-course dining experiences. Maenam’s sister restaurants—including Longtail Kitchen, Fat Mao Noodles, and Sen Pad Thai—offer unique and diverse menus, each bringing a different taste of Thai-inspired cuisine to various locations in Vancouver.

The **Restaurant Reservation System** is a Python-based software designed to streamline the booking process for Maenam and its sister restaurants, enabling patrons to easily reserve their preferred dining experiences. 

Currently, the system **supports customer interactions**, such as:
- Making reservations.
- Joining the restaurant waitlist.
- Modifying or canceling reservations or waitlist entries.

Features for **restaurant managers and staff**, such as managing table availability and tracking waitlisted customers, are planned for future iterations but are **not yet implemented**.

### Why the Project Is Useful

This project addresses key challenges in restaurant operations, including:
- Preventing double bookings or overbooking.
- Managing customer flow during peak dining hours.
- Optimizing table allocation.
- Handling reservations for special occasions or specific requirements.

By automating reservation management and waitlist tracking, the system reduces errors, improves efficiency, and enhances customer satisfaction.

Key features include:
- Easy creation of customer profiles.
- Real-time table availability checks.
- Automated handling of reservations and waitlists.
- Integration with restaurant-specific data, such as operating hours and table sizes.

### Who Will Use It

The **Restaurant Reservation System** is currently designed for:
- **Customers**: To book reservations or join a waitlist at participating restaurants.

Future versions of the system will expand to include:
- **Restaurant Managers**: To manage reservations, waitlists, and customer interactions.
- **Restaurant Staff**: To access reservation details, check table availability, and assist customers.

### Features

- **Customer Management**: Add and manage customer information.
- **Table Management**: Check table availability, reserve, and release tables.
- **Reservation System**: Create and manage reservations.
- **Waitlist**: Add customers to a waitlist when no tables are available.

*Note: Some features, such as table management and detailed waitlist tracking, are currently under development and are not available in this version.*

### Classes

1. **Customer**: Represents a customer with details like name, phone number, and email.
2. **Table**: Handles table attributes, availability, and reservations.
3. **Reservation**: Represents a confirmed booking.
4. **Waitlist**: Manages customers awaiting available tables.
5. **Restaurant**: Oversees reservations, waitlists, and tables for a specific restaurant.
6. **ReservationSystem**: Serves as the core manager for customers, reservations, and restaurants.

---

## Getting Started

### Prerequisites

To use this project, ensure you have the following installed:
- **Python 3.9 or later**

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/duanmulinfeng/RESERVATION-SYSTEM-FOR-MAENAM.git
   cd RESERVATION-SYSTEM-FOR-MAENAM

### Usage

Explain how to run and use the project:

```markdown
### Usage

1. **Run the System**:
   To start the program, navigate to the project directory and execute:
   python _main_.py

### Example Scenarios

Provide step-by-step instructions or examples to show how users can perform common tasks:

```markdown
### Example Scenarios

- **Make a Reservation**:
  1. Launch the program.
  2. Enter customer details (e.g., name, phone number, email).
  3. Select a date, time, and table size.
  4. Confirm the reservation.

- **Add to Waitlist**:
  1. Attempt to book a table when none are available.
  2. The system will automatically add the customer to the waitlist.
  3. Once a table becomes available, the customer will be notified.

- **Modify a Reservation**:
  1. Retrieve the reservation by providing your phone number
  2. Update the date, time, or other details.
  3. Save changes to confirm the modification.
