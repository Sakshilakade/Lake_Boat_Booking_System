🚤 Rankala Lake Boat Booking System

A Java Swing-based desktop application developed to manage boat reservations and inventory at Rankala Lake, Kolhapur, Maharashtra, India.

The system provides separate interfaces for administrators and users, featuring boat inventory management, seat-based reservations, booking history, revenue tracking, and interactive dashboards.

---

📌 About the Project

The Rankala Lake Boat Booking System is designed to make boat reservation and management more organized and convenient.

Users can register, log in, explore available boats, select seats and time slots, and manage their bookings.

Administrators can manage boat inventory, monitor reservations, view registered users, and track revenue through a dedicated dashboard.

The application is developed entirely using Java and Java Swing.

✨ Features

👤 User Module

- User registration and login
- Personalized user dashboard
- Browse available boats
- Search for boats
- View boat details, prices, and availability
- Select boats and number of seats
- Choose booking time slots
- Enter customer and payment details
- Select payment methods
- View personal booking history
- Manage account settings
- Logout functionality

🔐 Admin Module

- Dedicated administrator login
- Admin dashboard with summary cards
- Add new boats
- Edit existing boat details
- Delete boats
- Manage boat names, types, prices, and seats
- Track total and available boat quantities
- View customer bookings
- View registered users
- Monitor revenue and booking summaries
- Access reports and analytics
- Manage application settings

🚤 Boat Inventory Management

- Maintain boat information and inventory
- Track total boat quantities
- Monitor available boat quantities
- Update inventory after successful bookings
- Automatically update boat availability status
- Display inventory details in organized tables

🎟️ Booking Management

- Seat-based reservation system
- Time-slot selection
- Seat availability validation
- Booking record creation
- Automatic inventory updates
- Personal booking history
- Booking information reflected across relevant dashboards

📊 Reports & Analytics

The application provides an overview of booking and inventory information through:

- Total revenue
- Tickets sold
- Total boats
- Available boats
- Booked boats

It also includes custom chart panels:

- "RevenueChartPanel.java"
- "BookingChartPanel.java"

🔄 Data Updates

Booking and administrative changes are reflected across relevant application sections, including:

- User dashboard
- Admin dashboard
- Boat cards
- Inventory tables
- Booking records
- Reports
- Revenue charts
- Booking charts

---

🛠️ Technology Stack

Technology| Purpose
Java| Core programming language
Java Swing| Desktop user interface
JFrame| Application windows
JPanel| Interface components
JTable| Inventory and booking tables
Java Preferences| Application preference storage
In-memory Collections| Application data management
Custom Swing Panels| Charts and visualizations

Application Type: Desktop Application
Architecture: Class-based Java application
Entry Point: "Main.java"

---

🏗️ Project Structure

The application is organized into separate classes for models, user interfaces, authentication, data management, and visualization.

Class| Description
"Main.java"| Application entry point
"LoginPage.java"| Login and registration
"DataStore.java"| Central data storage and business logic
"Boat.java"| Boat inventory model
"Booking.java"| Booking model
"UserAccount.java"| User account model
"UserDashboard.java"| User dashboard interface
"AdminDashboard.java"| Administrator dashboard
"Dashboard.java"| Shared and legacy dashboard functionality
"BookingPage.java"| Standalone booking dialog
"RevenueChartPanel.java"| Revenue visualization
"BookingChartPanel.java"| Booking visualization

---

💾 Data Storage

The application currently uses:

- In-memory Java Collections: For managing application data.
- Java Preferences: For storing application preferences.

The project does not currently use an external database such as MySQL.

---

🎨 User Interface

The application follows a modern desktop design with:

- Light blue-gray background
- Dark navy sidebar navigation
- White and near-white cards
- Rounded borders
- Styled Swing tables
- Segoe UI typography
- Green indicators for available boats
- Red indicators for booked boats
- Dashboard cards and organized navigation

---

🚀 Getting Started

Prerequisites

- Java Development Kit (JDK)
- Java-compatible IDE such as:
  - Visual Studio Code
  - IntelliJ IDEA
  - Eclipse

Installation

1. Clone the repository

git clone https://github.com/Sakshilakade/Lake_Boat_Booking_System.git

2. Open the project

Open the cloned project folder in your preferred Java IDE.

3. Configure Java

Ensure that the required JDK is installed and configured.

4. Run the application

Locate "Main.java" and execute it to launch the application.

---

📍 Project Location

Rankala Lake, Kolhapur, Maharashtra, India

---

🎯 Project Objective

To develop a Java-based desktop application that simplifies boat reservations and provides an organized solution for managing boat inventory, customer bookings, users, and revenue information.

---

🔮 Future Improvements

- Database integration for persistent storage
- Online payment gateway integration
- Booking cancellation and refund management
- Improved reservation tracking
- Additional reporting features

---

👩‍💻 Developer

Developed as an individual Java project.

GitHub Repository:
https://github.com/Sakshilakade/Lake_Boat_Booking_System

---

⭐ If you find this project interesting, feel free to explore the repository!
