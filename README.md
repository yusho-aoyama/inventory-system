# Inventory System

Inventory system using PHP and SQL for class assessment  
(Information Technology – Certificate IV (Web developmet) at North Metropolitan TAFE, Australia)

---

## 📝 Overview

This project is an Inventory Management System developed mainly using **PHP** and **SQL**.  
The goal is to create a website for a small retail shop where:

- Users can browse available products.
- Admins can manage inventory via a simple CMS.

This is a learning project, with the possibility of adding basic e-commerce features in the future.

---

## 🚀 Features

### 👥 User
- Can view products on the website.
- Can add products to the cart.
- Can check and remove items from the cart.

### 🔧 Admin
- Can log in to the admin dashboard.
- Can view a list of all items stored in the database.
- Can check item details (e.g., product number, name, image, stock quantity, and status).
- Can manage items in the list (add, delete, update status, and edit details).

---

## 🧪 Planned Features (Future Implementation)

### User
- Search for items using a search bar.
- Sign up and log in using email and password.
- Checkout (purchase) items.
- Add items to "My List" (wishlist or saved items).

### Admin
- Sort items by product number, name, stock quantity, and status.

---

## 🛠️ Technologies Used
- **PHP** – Backend logic
- **MySQL** – Database management
- **HTML/CSS/JavaScript** – Frontend (if applicable)
- **XAMPP** – Local development environment (Apache & MySQL)

---

## ⚙️ Installation

### Prerequisites
Make sure you have the following installed:
- PHP >= 7.4
- MariaDB (MySQL-compatible)
- XAMPP (recommended, includes Apache, PHP, and MariaDB)

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/inventory-system.git
   cd inventory-system

2, Import the database schema:
   Use phpMyAdmin (included with XAMPP) to import database/schema.sql.

3, Configure database connection:
   Edit config/database.php and input your database credentials (host, database name, username, password).

4, Start local server using XAMPP:
   Place project files inside the htdocs folder.
   Launch Apache and MySQL (MariaDB) via XAMPP Control Panel.

## 🌐 Usage
As a user:
Open your browser and go to: http://localhost/inventory-system
You can browse and add items to your cart.

As an admin: 
Open your browser and go to: http://localhost/inventory-system/admin
You can log in to the admin panel to manage inventory.

## 📄 License
This project is licensed under the MIT License.

## 🙏 Acknowledgements
Created as part of the Web Development course at North Metropolitan TAFE.

## Contact
Developed by Yusho ([Yusho Aoyama](https://github.com/yusho-aoyama))
