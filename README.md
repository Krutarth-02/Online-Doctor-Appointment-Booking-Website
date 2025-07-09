# 🏥 Online Doctor Appointment Booking Website

This is a web-based **Doctor Appointment Booking System** built using **PHP, MySQL, HTML, CSS, and JavaScript**.  
It allows patients to book, view, and manage appointments with doctors, and enables admins to manage doctors, appointments, and feedback.

---

## 🚀 Live Demo

<!-- Uncomment and add your URL if hosted -->
<!-- [View Live Website](https://yourwebsite.com) -->

---

## 📌 Key Features

### 👤 User (Patient) Panel
- Register and login with secure credentials
- Book appointments with available doctors
- View, reschedule, or cancel appointments
- View doctor profiles and specializations
- Download appointment PDFs

### 👨‍⚕️ Admin Panel
- Login with admin credentials
- Add / Edit / Delete doctor profiles
- Set doctor availability and specializations
- View and manage all patient appointments
- Approve or cancel bookings
- Manage user feedback and patient records

---

## 🛠 Tech Stack

| Technology  | Usage                          |
|-------------|--------------------------------|
| PHP         | Backend & server-side logic    |
| MySQL       | Database                       |
| HTML/CSS    | Frontend structure and design  |
| JavaScript  | Client-side interactivity      |
| Bootstrap   | Responsive UI design (optional)|
| TCPDF       | PDF generation (for reports)   |

---

## 🗃 Database

Database Name: `healthcare`

### 🔧 Tables
- `user` — stores patient details  
- `doctor` — stores doctor profiles  
- `appointments` — stores bookings  
- `feedback` — stores patient feedback  

> All database scripts are included in the `/database` or `/sql` folder.


## 📦 Installation

# Clone the repository
git clone https://github.com/yourusername/doctor-appointment-system.git

# Move into the project folder
cd doctor-appointment-system

# Place the project in your local server (XAMPP/htdocs or WAMP/www)

# Import the database
# Open phpMyAdmin and import `healthcare.sql` file

# Start Apache and MySQL from XAMPP/WAMP
