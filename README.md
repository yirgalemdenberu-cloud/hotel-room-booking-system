# hotel-room-booking-system

A web-based platform for managing hotel room reservations, user accounts, and booking details.

## Features
* **User Authentication:** Secure registration and login for guests and administrators.
* **Room Exploration:** Browse available rooms with details, pricing, and amenities.
* **Booking Management:** Select dates, book rooms, and view reservation status.
* **Admin Dashboard:** Manage rooms, view overall bookings, and update reservation statuses.

## Technologies Used
* **Frontend:** HTML5, CSS3, JavaScript
* **Backend:** PHP (Procedural/OOP)
* **Database:** MySQL / MariaDB
* **Development Server:** XAMPP / WAMP

## Test Credentials (For Evaluation)
* **Admin Account:**
  * **Email/Username:** `admin@hotel.com`
  * **Password:** `admin123`
* **Guest User Account:**
  * **Email/Username:** `user@gmail.com`
  * **Password:** `user123`

## Local Setup & Installation Instructions
1. Download and install **XAMPP** or **WAMP**.
2. Clone or extract this project directory into the `htdocs` folder:
   `C:\xampp\htdocs\hotel-room-booking-system`
3. Start the **Apache** and **MySQL** services from the XAMPP Control Panel.
4. Open your Web Browser and navigate to `http://localhost/phpmyadmin/`.
5. Create a new database named **`hotel_db`**.
6. Import the included database script file: `database/hotel_db.sql`.
7. Access the application in your browser at:
   `http://localhost/hotel-room-booking-system`
