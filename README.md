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

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/doctor-appointment-system.git

# Move into the project folder
cd doctor-appointment-system

# Place the project in your local server (XAMPP/htdocs or WAMP/www)

# Import the database
# Open phpMyAdmin and import `healthcare.sql` file

# Start Apache and MySQL from XAMPP/WAMP
Then visit: http://localhost/doctor-appointment-system/

📁 Folder Structure
📂 doctor-appointment-system/
├── 📁 admin/           # Admin dashboard & pages
├── 📁 user/            # User (patient) pages
├── 📁 assets/          # CSS, JS, images
├── 📁 includes/        # Header, footer, DB config
├── 📁 sql/             # Database SQL file
├── index.php           # Home page
├── login.php           # Login page
├── register.php        # User registration
🔐 Login Credentials (Demo)
Admin Login
Username: admin

Password: admin123

User Login
Register as a new patient from register.php

📄 License
This project is open-source and available for personal and academic use.

🙋‍♂️ Author
Made with ❤️ by [Your Name]
📧 Email: your.email@example.com
🔗 GitHub: @yourusername


---
# 🏥 Doctor Appointment Booking Website

A responsive, web-based system that allows patients to book doctor appointments online, and provides an admin dashboard for managing doctors, appointments, and feedback.

---

## 🚀 Features

### 👤 Patient Panel
- Patient registration & login
- Search doctors by specialization
- Book/reschedule/cancel appointments
- View doctor details
- Download appointment PDF

### 🛡 Admin Panel
- Admin login
- Add/edit/delete doctor profiles
- Set doctor availability
- Approve or reject appointments
- Manage patient feedback & records

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **PDF:** TCPDF Library (for PDF generation)

---

## 🗃 Database

- **Database Name:** `healthcare`
- **Main Tables:**
  - `user` – stores patient info
  - `doctor` – stores doctor profiles
  - `appointments` – stores appointment bookings
  - `feedback` – stores patient reviews

> SQL file included in `/sql/healthcare.sql`

---

## 📁 Folder Structure

📦 doctor-appointment-website/
├── admin/ → Admin dashboard files
├── user/ → Patient panel files
├── assets/ → CSS, JS, images
├── includes/ → DB config, headers, etc.
├── index.php → Homepage
├── login.php → Login page
├── register.php → Registration page
├── sql/ → SQL database file


---

## ⚙️ Installation (Localhost)

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/online-doctor-appointment-booking-website.git
Move project to htdocs (XAMPP) or www (WAMP).

Import healthcare.sql in phpMyAdmin.

Start Apache & MySQL.

Visit: http://localhost/Online-Doctor-Appointment-Booking-Website

🔐 Demo Credentials
Admin Login:

Username: admin

Password: admin123

Patient Login:

Register at /register.php

👨‍💻 Author
Made with ❤️ by Krutarth Khadodiya
🔗 GitHub: krutarth-02
📧 Email: krutarthkhadodiya2@gmail.com
