# ZAYAS Simple E-commerce Website

A simple e-commerce website for ZAYAS clothing store, built with PHP following the MVC architecture pattern.

**Developed by: ZAYNAB AITADDI and ASMAE DAOUAD**

## 📝 Project Overview

ZAYAS Simple is a lightweight e-commerce platform specifically designed for clothing retail, with a focus on Islamic fashion items like abayas, dresses, and hijabs. The application follows the Model-View-Controller (MVC) architecture pattern to ensure maintainable and scalable code structure.

## ✨ Features

- **User Authentication**
  - Register, login, and logout functionality
  - Password reset capability
  - User account management

- **Product Management**
  - Browse products 
  - Detailed product view
  - Image gallery

- **Shopping Experience**
  - Shopping cart functionality
  - Wishlist management
  - Order processing and tracking

- **Delivery System**
  - Delivery personnel portal
  - Dashboard with delivery statistics
  - Delivery status updates

- **Order Status System**
  - Comprehensive order status tracking
  - Multiple status options (Pending, Assigned, In-Transit, etc.)
  - Status flow management

## 🗄️ Database Structure

- **`users`** - User information and authentication
- **`products`** - Product details
- **`orders`** - Order information
- **`order_items`** - Items in each order
- **`wishlist`** - User wishlist items
- **`delivery`** - Delivery information
- **`cart`** - Shopping cart items
- **`password_reset_tokens`** - Password reset functionality

## 🚀 Setup Instructions

### Automatic Setup
1. Place the project in your web server's document root (e.g., `xampp/htdocs/ZAYAS_simple`)
2. Ensure your MySQL server is running (e.g., through XAMPP control panel)
3. Navigate to `http://localhost/ZAYAS_simple/setup.php` in your web browser
4. Click on "Set Up Database" to create the database, tables, and sample data
5. Once setup is complete, click on "Go to Website" to access the application
6. Alternatively, access the website directly at `http://localhost/ZAYAS_simple`

### Manual Configuration
If you need to manually configure the database:
- Configure database connection in `config/Database.php`
- Default configuration:
  - Host: localhost
  - Username: root
  - Password: (empty)
  - Database: zayas_simple
- You can also run the SQL scripts directly from the provided SQL file

## 💻 Technologies Used

- **Backend**: PHP
- **Database**: MySQL
- **Frontend**:
  - HTML
  - CSS
  - JavaScript (minimal)
  - Bootstrap 5

## 👤 Default Accounts

### Admin Account
- Email: admin@zayas.com
- Password: 123456

---

© 2025 ZAYAS Simple E-commerce
