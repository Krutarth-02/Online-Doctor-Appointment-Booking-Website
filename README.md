# 🩺 Online Doctor Appointment Booking Website

This is a web-based application where patients can register, log in, and book appointments with doctors. Admins can manage doctors, appointments, and user feedback. The site is built using PHP, MySQL, HTML, CSS, and JavaScript.

---

## 🚀 Features

### 👨‍⚕️ For Users (Patients)
- Register & Login
- Book appointments with doctors
- View, cancel, or reschedule appointments
- View doctor profiles and specializations
- Check appointment history

### 🛠️ For Admin
- Admin login
- Add, update, or delete doctors
- Manage appointment requests
- Approve or cancel appointments
- View and manage patient feedback

---

## 🧾 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

---

## 📂 Folder Structure

project/
│
├── admin/ # Admin panel files
├── user/ # User (patient) panel files
├── css/ # Global stylesheets
├── images/ # Profile images, assets
├── js/ # JavaScript files
├── config/ # DB config files
├── includes/ # Reusable PHP components
├── index.php # Homepage
└── README.md # This file

## 🛠️ How to Use

### 🔧 1. Clone the Repository

git clone https://github.com/yourusername/online-doctor-booking.git
🧑‍💻 2. Setup Local Server
Use XAMPP/WAMP/LAMP and place the project folder inside the htdocs/ directory.

🗄️ 3. Import the Database
Open phpMyAdmin

Create a new database (e.g., healthcare)

Import the provided .sql file inside the database/ folder

⚙️ 4. Configure Database Connection
Edit config/db.php or similar config file to update:

$host = 'localhost';
$username = 'root';
$password = '';
$database = 'healthcare';
🔐 Login Credentials
✅ User (Patient)
Register via /user/register.php

Then log in at /user/login.php

🛡️ Admin
Access: /admin/login.php

Default credentials (change after first login):

Username: admin
Password: admin123
📌 Notes
Make sure Apache and MySQL are running in your XAMPP/WAMP

For any image upload issues, make sure the images/ folder is writable

Designed to be mobile-responsive

📞 Contact
For any queries, feel free to reach out at:
📧 [krtuarthkhadodiya2@gmail.com]
📸 Instagram: @unbreakable_krutarth
