# 🏨 Hotel Reservation System (Java)

A Java-based console application that simulates a basic hotel booking system. It allows users to search, book, and manage hotel rooms with persistent data storage using file I/O.

---

## 🚀 Features

- 🔍 Search rooms by category and availability
- 🛏️ Room types: **Standard**, **Deluxe**, **Suite**
- 📅 Make or cancel reservations
- 💳 Simulated payment process
- 📋 View reservation details
- 💾 File-based data persistence using `.txt` files

---

## 📁 Project Structure

HOTELRESERVATIONSYSTEM/
│
├── BookingManager.java    # Handles booking and cancellation
├── FileManager.java       # Manages file I/O for bookings
├── HotelSystem.java       # Main hotel system logic
├── Reservation.java       # Reservation model
├── Room.java              # Room model with category
├── User.java              # User model
├── bookings.txt           # Text file storing booking data
├── README.md              # Project documentation (this file)




> ℹ️ `.class` files are generated after compilation – no need to include them in your repo.

---

## ▶️ How to Run

1. **Compile the Project**
   ```bash
   javac *.java
2.**Run the Main Class**
    ```bash
   java HotelSystem
