Medical Prescription Upload System

🎯 Project Overview

A secure web application that allows patients to upload prescription images and receive quotations from pharmacies efficiently and safely.

📋 Features Completed

Part A - User System

✅ User Registration (Name, Email, Address, Contact, DOB)
✅ User Login System
✅ Upload Prescription (Max 5 images, notes, delivery details)
✅ Prescription status tracking

Part B - Pharmacy System

✅ Pharmacy login system
✅ View uploaded prescriptions
✅ Create detailed quotations with medicine list
✅ Email notifications to users
✅ Accept/Reject quotation handling

🛠️ Technology Stack

Backend: PHP 7.4+, MySQL
Frontend: HTML5, CSS3, JavaScript, Font Awesome
Database: MySQL with PDO
File Upload: PHP file handling
Email: PHP mail() function

📁 Project Structure
prescription_system/
├── config/database.php          # Database connection
├── includes/                    # Common files
│   ├── header.php
│   └── footer.php
├── uploads/prescriptions/       # Upload directory
├── css/style.css               # Main stylesheet  
├── js/script.js                # JavaScript functions
├── user/                       # User pages
│   ├── register.php
│   ├── login.php
│   ├── dashboard.php
│   ├── upload_prescription.php
│   └── view_quotations.php
├── pharmacy/                   # Pharmacy pages
│   ├── login.php
│   ├── dashboard.php
│   ├── view_prescriptions.php
│   └── create_quotation.php
├── api/logout.php             # Logout functionality
└── index.php                  # Home page


🎨 Key Features

File Upload System

Drag & drop interface
Image preview functionality
File type validation (JPG, PNG)
Size limit (5MB per image)
Maximum 5 images per prescription

Quotation System

Dynamic item addition
Real-time price calculation
Email notifications
Accept/Reject functionality

🔄 User Workflow

Patient Registration/Login
Upload Prescription (images + delivery details)
Wait for Quotations (email notifications)
Review & Accept/Reject quotations
Order Confirmation

🏥 Pharmacy Workflow

Pharmacy Login
View New Prescriptions
Create Detailed Quotations
Send to Patients (automatic email)
Process Accepted Orders

📱 Responsive Design

Mobile-friendly interface
Grid layouts for different screen sizes
Touch-friendly buttons and forms
Optimized image viewing


🎉 Project Complete!


🌐 Complete URL Structure:

🏠 Main Entry Points:
http://localhost/prescription_system_1/                    # Home page
http://localhost/prescription_system_1/index.php          # Home page (same)
👥 User/Patient URLs:
http://localhost/prescription_system_1/user/register.php      # User registration
http://localhost/prescription_system_1/user/login.php         # User login  
http://localhost/prescription_system_1/user/dashboard.php     # User dashboard (after login)
http://localhost/prescription_system_1/user/upload_prescription.php  # Upload prescription
http://localhost/prescription_system_1/user/view_quotations.php      # View quotations
🏥 Pharmacy URLs:
http://localhost/prescription_system_1/pharmacy/login.php         # Pharmacy login
http://localhost/prescription_system_1/pharmacy/dashboard.php     # Pharmacy dashboard
http://localhost/prescription_system_1/pharmacy/view_prescriptions.php  # View prescriptions
http://localhost/prescription_system_1/pharmacy/create_quotation.php    # Create quotations
🔐 Demo Login Credentials:
Pharmacy Login:

🎯 Main Testing URL:

🔥 START HERE: http://localhost/prescription_system_1/


URL: http://localhost/prescription_system_1/pharmacy/login.php
Email: pharmacy@citymed.lk
Password: password

🚀 Quick Start Testing URLs:
1️⃣ Start Here:
http://localhost/prescription_system_1/
2️⃣ Register New User:
http://localhost/prescription_system_1/user/register.php
3️⃣ Login as Pharmacy (Demo):
http://localhost/prescription_system_1/pharmacy/login.php
4️⃣ Full System Test Flow:

Register user → http://localhost/prescription_system_1/user/register.php
Login user → http://localhost/prescription_system_1/user/login.php
Upload prescription → http://localhost/prescription_system_1/user/upload_prescription.php
Login pharmacy → http://localhost/prescription_system_1/pharmacy/login.php
Create quotation → http://localhost/prescription_system_1/pharmacy/view_prescriptions.php
Accept quotation → http://localhost/prescription_system_1/user/view_quotations.php



