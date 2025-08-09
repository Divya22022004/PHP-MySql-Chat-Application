# PHP MySQL Chat Application – MyChat

A real-time, web-based chat application built using **PHP**, **MySQL**, **CSS**, **Bootstrap**, and **JavaScript**.  
It provides user authentication, friend search, profile management, and instant messaging features.

---

## 🚀 Features

- **User Authentication**
  - Sign In / Sign Up
  - Forgot Password & Password Recovery
  - Change Password functionality

- **User Profile Management**
  - Upload & update profile picture
  - Edit personal information (username, email, country, gender)
  - Privacy and account settings

- **Chat Functionality**
  - Real-time messaging between users
  - Online/offline status indicator
  - Message read/unread tracking
  - Conversation history with timestamps

- **Friend Management**
  - Search for friends by name or country
  - Start private chat sessions

- **Responsive UI**
  - Mobile-friendly design with Bootstrap
  - Clean and intuitive chat interface

---

## 🛠️ Technologies Used

- **Backend:** PHP (Procedural)
- **Frontend:** HTML5, CSS3, Bootstrap, JavaScript, jQuery
- **Database:** MySQL
- **Server:** Apache (XAMPP/WAMP/LAMP)
- **Other:** AJAX for dynamic data updates

---

## 📂 Project Structure

- `signin.php` / `signup.php` – User login & registration
- `home.php` – Chat interface
- `find_friends.php` – Search users
- `upload.php` – Profile picture upload
- `account_settings.php` – Account details management
- `change_password.php` – Password change
- `forgot_pass.php` / `create_password.php` – Password recovery
- `include/` – Database connection & utility files
- `css/` – Stylesheets for pages
- `images/` – Profile pictures and UI assets

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/php-mysql-chat-app.git
# MyChat – PHP MySQL Chat Application

A real-time, web-based chat application built using **PHP**, **MySQL**, **CSS**, **Bootstrap**, and **JavaScript**.

---

## 📂 Project Setup

### 1️⃣ Move the Project to Server Root
- **XAMPP:** Copy the `MyChat` folder to `htdocs`
- **WAMP:** Copy the `MyChat` folder to `www`
- **LAMP:** Copy the `MyChat` folder to `/var/www/html`

---

### 2️⃣ Import the Database
1. Open **phpMyAdmin** in your browser (`http://localhost/phpmyadmin`)
2. Create a new database named **`mychat`**
3. Import the provided SQL file (`database.sql`) into this database

---

### 3️⃣ Configure Database Connection
1. Open `include/connection.php`
2. Update the following with your own settings:
   ```php
   $con = mysqli_connect("localhost", "root", "", "mychat") 
       or die("Connection was not established");

### 4️⃣ Run the Application
Start Apache and MySQL services in XAMPP/WAMP/LAMP

Open your browser and go to:
http://localhost/MyChat
