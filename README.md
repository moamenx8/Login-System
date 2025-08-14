#🔐 PHP Login System

A simple and secure login system built with PHP and MySQL.
Designed with security, error handling, and user experience in mind.

🌐 Live Demo

👉 Visit the live website

📁 Features

✅ Password Hashing using password_hash() and password_verify()

✅ Duplicate Email Check to prevent multiple accounts with the same email

✅ Error Handling for clean user feedback and developer logging

✅ Basic Session Management for login/logout

✅ Connected to MySQL Database (local or remote)

📸 Screenshots

(You can add screenshots of the register/login page here)
Example:


🛠️ Technologies Used

PHP

MySQL (with MySQLi)

HTML/CSS

InfinityFree Hosting (Free)

GitHub for version control

🚀 How to Run Locally

Clone the repository:

git clone https://github.com/moamenx8/Login-System.git


Import the SQL file into your database (e.g., using phpMyAdmin).

Configure the database connection inside handlelogin.php and handleregister.php.

Run the project using XAMPP, WAMP, or deploy it to a server.

🔒 Security Notes

Passwords are securely hashed in the database.

Prepared statements or proper escaping are recommended to prevent SQL injection.

You can enhance it further with:

CSRF Protection

Two-Factor Authentication (2FA)

CAPTCHA

📂 File Structure
Login-System/
├── index.php
├── register.php
├── profile.php
├── handle/
│   ├── handlelogin.php
│   └── handleregister.php
├── CSS/
│   └── style.css
├── images/
│   └── user uploads
└── database.sql

🤝 Contributions

Feel free to fork, improve, and submit pull requests!
Feedback is always welcome.

📬 Contact

Developed by Moamen Elsayed
📧 LinkedIn (optional)
💻 GitHub: @moamenx8
