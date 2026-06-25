# ELUX-The-Future-of-Online-Shopping

ELUX is a modern web-based E-Commerce platform developed using PHP, MySQL, HTML, CSS, JavaScript, Bootstrap, and AJAX. The system provides a seamless online shopping experience where users can browse products, manage their cart and wishlist, place orders, and manage their profiles. It also includes an admin panel for product management and store monitoring.

---

## 🚀 Features

### 👤 User Features
- User Registration & Login
- Secure Session Management
- Browse Products
- Product Search Functionality
- Category-Based Product Filtering
- Add to Cart
- Update Cart Items
- Wishlist Management
- Checkout System
- Order Placement
- User Profile Management
- Responsive Design

### 🛠️ Admin Features
- Admin Authentication
- Dashboard Analytics
- Product Management
- Add New Products
- Edit Existing Products
- Delete Products
- View Total Products
- View Total Users
- View Total Orders
- Revenue Overview

---

## 📂 Project Structure

```text
ELUX/
│
├── index.php                # Homepage & Product Listing
├── login.php                # User Login
├── signup.php               # User Registration
├── logout.php               # Logout System
├── profile.php              # User Profile
│
├── cart.php                 # Shopping Cart
├── wishlist.php             # Wishlist
├── checkout.php             # Checkout Page
│
├── ajax_cart.php            # AJAX Cart Operations
├── ajax_wishlist.php        # AJAX Wishlist Operations
│
├── admin_dashboard.php      # Admin Dashboard
├── add_product.php          # Add Product
├── edit_product.php         # Edit Product
│
├── navbar.php               # Navigation Bar
├── footer.php               # Footer
├── style.css                # Styling File
│
├── db.php                   # Database Connection
├── database.sql             # Database Schema
│
└── uploads/                 # Product Images
```

---

## 💻 Technologies Used

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- AJAX
- Font Awesome

### Backend
- PHP

### Database
- MySQL

---

## 🗄️ Database Tables

The system uses the following database tables:

### Users
Stores customer and admin accounts.

### Products
Stores product details including:
- Product Name
- Description
- Category
- Price
- Image

### Cart
Stores products added to cart by users.

### Wishlist
Stores products saved for later purchase.

### Orders
Stores placed orders.

### Order Items
Stores products associated with each order.

---

## ⚙️ Installation Guide

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/elux.git
```

### Step 2: Move Project

Place the project folder inside:

```text
xampp/htdocs/
```

### Step 3: Start Apache & MySQL

Open XAMPP Control Panel and start:

- Apache
- MySQL

### Step 4: Create Database

1. Open phpMyAdmin
2. Create a database named:

```sql
shop_db
```

3. Import:

```text
database.sql
```

### Step 5: Configure Database

Open:

```php
db.php
```

Update credentials if required:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "shop_db";
```

### Step 6: Run Project

Open browser:

```text
http://localhost/elux
```

---

## 🎯 Key Highlights

- Modern User Interface
- Fully Responsive Design
- Dynamic Product Filtering
- AJAX-Based Cart & Wishlist
- Order Management System
- Admin Dashboard
- Product Image Support
- Real-Time User Experience

---

## 🔐 User Roles

### Customer
- Browse Products
- Add to Cart
- Manage Wishlist
- Place Orders
- Update Profile

### Administrator
- Manage Products
- View Analytics
- Monitor Orders
- Store Management

---

## 📸 Screens Included

- Login Page
- Registration Page
- Home Page
- Product Listing
- Shopping Cart
- Wishlist
- Checkout Page
- User Profile
- Admin Dashboard
- Product Management

---

## 🌟 Future Enhancements

- Online Payment Gateway Integration
- Product Reviews & Ratings
- Order Tracking
- Email Notifications
- Discount Coupons
- Inventory Management
- Sales Reports
- Multi-Vendor Support
- AI Product Recommendation System



## 📜 License

This project was developed for educational and academic purposes.

© 2026 ELUX – Modern Shopping Redefined
