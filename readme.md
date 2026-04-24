# 🩸 BloodChain - Blood Donation & Request System

## 📌 Overview

**BloodChain** is a full-stack web application designed to digitize and streamline the blood donation process. It connects **donors**, **patients**, and **administrators** on a centralized platform, enabling real-time blood requests, donation management, and efficient allocation.

The system eliminates manual processes, reduces delays, and ensures quick access to blood during medical emergencies.

---

## 🎯 Problem Statement

Traditional blood donation systems are:

* Manual and time-consuming
* Lack real-time coordination
* Not transparent or centralized

Patients often struggle to find donors quickly, which can lead to critical delays.

---

## 💡 Solution

BloodChain provides a **web-based solution** that:

* Connects donors and patients instantly
* Allows real-time blood request and donation tracking
* Enables admin-controlled verification and allocation
* Maintains a centralized database of blood inventory

---

## 🚀 Features

### 👤 Donor Module

* Register and login securely
* Submit blood donation requests
* View donation history and status
* Update personal details

### 🏥 Patient Module

* Register and request blood
* Specify blood group, units, and urgency
* Track request status (Pending / Approved / Rejected)

### 🛠 Admin Module

* Manage donors and patients
* Approve or reject donation and request entries
* Allocate blood based on availability
* Monitor blood inventory

### 🔐 Security Features

* Authentication and session management
* Input validation (frontend + backend)
* Protection against SQL Injection (basic level)

---

## 🧱 System Architecture

The application follows a **3-tier architecture**:

1. **Frontend (Client Side)**

   * HTML, CSS, JavaScript
   * Handles UI and user interaction

2. **Backend (Server Side)**

   * PHP
   * Handles business logic, authentication, and requests

3. **Database Layer**

   * MySQL
   * Stores users, donations, requests, and inventory

---

## 🛠 Tech Stack

| Layer    | Technology Used       |
| -------- | --------------------- |
| Frontend | HTML, CSS, JavaScript |
| Backend  | PHP                   |
| Database | MySQL                 |
| Server   | XAMPP (Apache)        |
| Tools    | VS Code, phpMyAdmin   |

---

## 📂 Project Structure

```
BloodChain/
│
├── admin/              # Admin dashboard & controls
├── donor/              # Donor module
├── patient/            # Patient module
├── includes/           # Database connection & common files
├── css/                # Stylesheets
├── js/                 # JavaScript files
├── images/             # Assets
├── index.php           # Homepage
└── README.md
```

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Install XAMPP

Download and install XAMPP from the official website.

### 2️⃣ Clone Repository

```bash
git clone https://github.com/your-username/BloodChain-System.git
```

### 3️⃣ Move Project

Copy the project folder to:

```
C:/xampp/htdocs/
```

### 4️⃣ Start Server

* Start **Apache** and **MySQL** from XAMPP Control Panel

### 5️⃣ Setup Database

* Open `http://localhost/phpmyadmin`
* Create a database (e.g., `bloodchain`)
* Import the provided `.sql` file

### 6️⃣ Run Project

Open browser and go to:

```
http://localhost/BloodChain-System
```

---

## 🧪 Testing

The system was tested using:

* Unit Testing
* Integration Testing
* System Testing
* UI Testing

### Sample Test Cases

* Valid login → Redirect to dashboard
* Invalid login → Error message
* Blood request → Confirmation message
* Unauthorized access → Redirect to login

---

## 📊 Key Achievements

* Developed a **fully functional full-stack application**
* Implemented **real-time request & donation workflow**
* Designed **responsive UI**
* Created **admin-controlled validation system**
* Built a **database-driven blood inventory system**

---

## ⚠️ Limitations

* Runs on local server (XAMPP)
* No real-time notifications (SMS/Email not integrated)
* No geolocation-based donor matching

---

## 🔮 Future Enhancements

* Deploy on cloud (AWS / Render / Railway)
* Add SMS & Email notifications
* Implement location-based donor search
* Mobile app integration
* Advanced security (JWT, encryption, HTTPS)

---

## 📷 Screenshots

(Add your project screenshots here — very important for GitHub impact)

---

## 🌍 Real-World Impact

This project helps:

* Reduce delays in emergency blood availability
* Improve healthcare response time
* Encourage voluntary blood donation

---

## 👨‍💻 Author

**Shivam Singh**

* 🎓 BSc IT Graduate (Mumbai University)
* 💻 Full Stack Developer | Data Science Enthusiast

---

## ⭐ Support

If you found this project useful:

* Star ⭐ the repository
* Share it with others
* Contribute for improvements
