# 💃 Dance Academy Registration System

> A web-based Dance Academy Management System that simplifies student registration, class management, teacher management, invoices, and administration through a centralized online platform.

---

# 🚀 Overview

Dance Academy Registration System is a web application developed to automate the process of managing dance academy registrations. The system allows students to browse available dance classes and register online, while administrators can manage classes, teachers, registrations, invoices, reports, and website content through a secure dashboard.

The application eliminates manual paperwork, improves registration efficiency, and provides an organized platform for academy management.

---

# ✨ Key Features

## 🔐 Admin Module

- Secure Admin Login
- Dashboard with Statistics
- Profile Management
- Change Password
- Password Recovery

---

## 🩰 Dance Class Management

- Add Dance Classes
- Update Class Details
- Delete Classes
- Upload Dance Images
- Manage Class Information

---

## 👨‍🏫 Teacher Management

- Add Teachers
- Update Teacher Details
- Manage Teacher Profiles

---

## 👩‍🎓 Student Registration

- Online Dance Class Registration
- View Registration Status
- Registration Remarks
- Registration Tracking

---

## 📑 Registration Management

- View New Registrations
- Accept Registrations
- Reject Registrations
- Add Remarks
- Search Registration by Registration Number

---

## 💰 Invoice Management

- Generate Invoices
- View Invoice Details
- Search Invoice
- Manage Payment Records

---

## 📊 Reports

- Between Date Reports
- Registration Reports
- Sales Reports
- Academy Statistics

---

## 🌐 Website Management

- Home Page
- About Us Page
- Contact Us Page
- Team Page
- Dance Classes Information

---

# 🏗️ System Architecture

```text
                 +-------------------+
                 |      Student      |
                 +---------+---------+
                           |
                  Online Registration
                           |
                  Dance Academy Website
                           |
      -----------------------------------------
      |               |              |
   Dance Classes   Registration   Contact
      |               |
      +---------------+
              |
        Admin Dashboard
      -----------------------
      |     |      |        |
   Classes Teachers Reports Invoice
              |
          MySQL Database
```

---

# ⚙️ Technology Stack

## Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap

---

## Backend

- PHP

---

## Database

- MySQL

---

## Web Server

- Apache Server (XAMPP)

---

## Development Tools

- XAMPP
- phpMyAdmin
- Visual Studio Code
- Google Chrome

---

# 📱 Features

✔ Online Dance Registration

✔ Teacher Management

✔ Class Management

✔ Invoice Generation

✔ Registration Reports

✔ Responsive Website

✔ Easy Navigation

✔ Secure Admin Panel

---

# 🔒 Security

- Admin Authentication
- Password Protection
- Secure Database Access
- Input Validation
- Session Management

---

# 📂 Project Structure

```text
Dance-Academy-Registration-System/

├── admin/
│   ├── dashboard/
│   ├── classes/
│   ├── teachers/
│   ├── registration/
│   ├── invoice/
│   └── reports/
│
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
├── includes/
├── database/
├── uploads/
├── index.php
├── login.php
├── config.php
└── README.md
```

---

# ⚡ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Dance-Academy-Registration-System.git
```

---

## Move Project

Copy the project into the XAMPP `htdocs` folder.

Example:

```text
C:\xampp\htdocs\Dance-Academy-Registration-System
```

---

## Import Database

- Open phpMyAdmin
- Create a new database
- Import the provided SQL file

---

## Configure Database

Update database credentials in:

```php
config.php
```

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "danceacademy";
```

---

## Run Application

Start:

- Apache
- MySQL

Visit:

```text
http://localhost/Dance-Academy-Registration-System
```

---

# 🎯 Objectives

- Digitize dance class registration
- Reduce manual paperwork
- Simplify student management
- Manage dance classes efficiently
- Maintain teacher records
- Generate reports automatically
- Improve academy administration

---

# 🌟 Key Highlights

- 🩰 Online Dance Registration
- 👨‍🏫 Teacher Management
- 📚 Dance Class Management
- 📊 Reports & Analytics
- 💰 Invoice Generation
- 🔍 Registration Search
- 🌐 Responsive Website
- 🔒 Secure Admin Panel

---

# 📸 Screenshots

Add screenshots of the application here.

Example:

```text
screenshots/

home.png

about.png

classes.png

registration.png

admin-dashboard.png

manage-classes.png

teachers.png

reports.png

invoice.png
```

---

# 🚀 Future Enhancements

- Online Payment Gateway
- Student Login Portal
- Attendance Management
- Course Completion Certificates
- SMS & Email Notifications
- Mobile Application
- AI-Based Class Recommendation
- Online Live Dance Classes
- Digital Fee Management

---

# 👨‍💻 Developed By

**Gayatri Shinde**

---

# 🎓 Academic Information

**Degree:** Bachelor of Science in Information Technology (B.Sc. IT)

**Project Type:** Academic Project

**Domain:** Web Development | Dance Academy Management System

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

Your support motivates future improvements and helps others discover the project.

---

# 📄 License

This project is developed for academic and educational purposes only.
