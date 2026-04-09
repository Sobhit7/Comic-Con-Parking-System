# Comic-Con-Parking-System
# 🚗 Parking Management System

A database-driven system designed to manage parking zones, spots, vehicles, sessions, payments, and ticketing efficiently.

---

## 📌 Features

- Manage parking zones and levels
- Categorize parking spots (General, VIP, etc.)
- Track vehicles and their categories
- Monitor parking sessions (entry & exit)
- Support multiple access types
- Handle payments (UPI, Cash, Card)
- Generate parking tickets

---

## 🗂️ Database Tables

- **parkingZone** – Stores zone details  
- **parkingSpot** – Stores individual parking spots  
- **parkingSpotCategory** – Defines spot categories  
- **Vehicles** – Stores vehicle information  
- **Vehicle_Category** – Defines vehicle types  
- **ParkingSession** – Tracks parking activity  
- **AccessCategory** – Defines access types  
- **payment** – Stores payment details  
- **Ticket** – Manages issued tickets  

---

## 🔗 Relationships

- One **zone** → many **parking spots**
- One **spot category** → many **spots**
- One **vehicle category** → many **vehicles**
- One **parking session** → one **vehicle**, one **spot**, one **access type**
- One **session** → one **payment** and one **ticket**


  

