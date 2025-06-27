# 🧑‍💼 Online Job Portal

This is a full-featured Online Job Portal developed using **PHP**, **HTML**, **CSS**, **JavaScript**, and **MySQL**. It allows job seekers to register and apply for jobs, while employers can post job listings and manage applications. This project is suitable for academic submission, small organizations, or learning purposes.

---

## 🚀 Features

- 👤 Job Seeker and Employer login/registration
- 📝 Post and manage job listings
- 🔍 Explore and apply for jobs
- 📄 Upload certificates and attachments
- 🔐 Password reset functionality
- 📬 Email integration for communication
- 📊 Admin and employee dashboards
- 📱 Responsive Bootstrap design

---

## 📁 Folder Structure

OnlineJobPortal/
├── Database/ # SQL database dump
├── Installation.txt # Manual installation instructions
└── System/ # Core application
├── app/ # Application logic/config (if any)
├── bootstrap/ # Bootstrap assets
├── css/ # Stylesheets
├── js/ # JavaScript files
├── icons/, images/ # Static assets
├── mail/ # Email-related components
├── ViewerJS/ # Document viewer
├── *.php # Main pages (login, register, job-list, etc.)



---

## ⚙️ Setup Instructions (Using AMPPS/XAMPP)

### 1. Requirements

- PHP 7.x or above
- MySQL
- AMPPS or XAMPP installed

### 2. Clone or Download the Repository

```bash
git clone https://github.com/Sumantrayadav/OnlineJobPortal.git


3. Move Project to Server Directory
Copy the System/ folder into:

C:\Ampps\www\OnlineJobPortal\ (for AMPPS)

C:\xampp\htdocs\OnlineJobPortal\ (for XAMPP)

4. Import the Database
Open phpMyAdmin

Create a new database (e.g., job_portal_db)

Import the .sql file from the Database/ folder

5. Update Database Configuration
Find the database config file (commonly in app/ or constants/) and update credentials:

php
Copy
Edit
$host = 'localhost';
$user = 'root';
$password = 'root'; // For AMPPS. Use '' (blank) for XAMPP
$dbname = 'job_portal_db';
6. Run the Application
In your browser, go to:

arduino
Copy
Edit
http://localhost/OnlineJobPortal/

👨‍💻 Developed By
Sumantra Yadav
BSc (Hons) Computer Systems Engineering
ISMT College

💼 Junior Software Developer at Data Pulse Systems (DPS)

💡 Founder of Tech-Integrators

📧 yadavbhunte51@gmail.com

🌐 GitHub: Sumantrayadav

🤝 Contributions
Contributions are welcome! Feel free to fork this repo and submit a pull request to improve functionality, UI, or add new features.





