# COVID-19 Testing Management System

A web-based **COVID-19 Testing Management System** built using PHP and MySQL to streamline the process of test registration, result management, and reporting.

## 🛠 Tech Stack

- **Language Used:** PHP 5.6, PHP 7.x  
- **Database:** MySQL 5.x  
- **User Interface:** HTML, AJAX, jQuery, JavaScript  
- **Compatible Browsers:** Mozilla Firefox, Google Chrome, IE8, Opera  
- **Software Required:** XAMPP / Wamp / Mamp / Lamp (anyone)  

## ✨ Features

- Secure **user authentication** and role-based access (Admin, Lab Technician, Patient).
- **Test registration** and real-time tracking of COVID-19 test results.
- **Dynamic dashboard** for monitoring pending and completed tests.
- **Efficient database management** to handle large-scale test data.
- **Automated report generation** for patients and admin users.

## 📂 Project Setup

### 1️⃣ Prerequisites
- Install **XAMPP, Wamp, Mamp, or Lamp**.
- Ensure **Apache** and **MySQL** services are running.

### 2️⃣ Installation Steps
1. Clone the repository:  
   ```bash
   git clone https://github.com/GaneshRenuse/Covid19-TMS-Project.git
   ```
2. Move the project folder to your server's root directory:
   - `htdocs` for XAMPP  
   - `www` for Wamp  
3. Import the database:
   - Open **phpMyAdmin**.
   - Create a new database (e.g., `covidtmsdb`).
   - Import the provided SQL file (`covidtmsdb.sql`).
4. Configure the database connection in `config.php`:
   ```php
   $host = "localhost";
   $user = "root";
   $password = "";
   $database = "covidtmsdb";
   ```
5. Start the server and access the system in your browser:
   ```
   http://localhost/covid19-testing-management/
   ```

## 📸 Screenshots  


## 🔒 Login Credentials (For Testing)
| Role  | Username | Password |
|--------|------------|------------|
| Admin | admin | Test@123 |

## 🏗 Future Enhancements
- Integration of **email/SMS notifications** for test results.
- Role-based **access control improvements**.
- **Analytics dashboard** for statistical insights.

## 🤝 Contributing
Contributions are welcome! Fork the repo, create a branch, and submit a pull request.

## 📜 License
This project is licensed under the **MIT License**.

---
