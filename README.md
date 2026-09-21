🍔 Food Ordering System
A comprehensive, web-based Food Ordering System built using PHP, HTML, CSS, JavaScript, and MySQL. This application allows customers to browse menus, add items to a cart, place food orders, and track them, while providing administrators with a robust dashboard to manage dishes, categories, coupons, delivery personnel, and incoming orders.

🚀 Features
Customer Features:
User Authentication: Secure registration and login system.

Interactive Menu: Browse food items categorized by type with rich details and prices.

Cart & Checkout: Add items to a shopping cart, apply coupon codes, and place orders smoothly.

Order Tracking: Keep track of current and past order histories.

Contact & About Pages: Built-in customer support and information pages.

Admin Dashboard:
Dashboard Analytics: Overview of system activity, revenue, and order statistics.

Dish & Category Management: Easily add, edit, or remove food items and categories.

Order Management: Monitor customer orders, update order statuses, and handle logistics.

Delivery Personnel Management: Assign and track delivery boys for food dispatch.

Coupon Management: Create and manage promotional discount codes.

Financial Tracking: Add and manage funds or balances within the system.

🛠️ Technology Stack
Frontend: HTML5, CSS3, JavaScript, Bootstrap, DataTables

Backend: PHP

Database: MySQL / MariaDB

Assets/Plugins: Bootstrap Datepicker, Custom Admin Dashboard Templates (Corona/Royal UI style)

⚙️ Installation & Setup Guide
Clone or Download the Repository:
Download and extract the zip file into your local server directory (e.g., htdocs in XAMPP or www in WampServer).

Database Setup:

Open phpMyAdmin via your local server (e.g., http://localhost/phpmyadmin).

Create a new database (refer to your SQL configuration files for the specific database name).

Import the provided .sql database schema file.

Configure Database Connection:

Locate the database configuration file within the project structure and update your credentials (host, username, password, database name) if necessary:

PHP
$conn = mysqli_connect("localhost", "root", "", "your_database_name");
Run the Application:

Start Apache and MySQL on your XAMPP/WAMP control panel.

Open your browser and navigate to the project folder:

Plaintext
http://localhost/food_ordering_system-main/
📂 Project Structure Overview
Plaintext
food_ordering_system-main/
│
├── about-us.php             # About Us page for customers
├── contact-us.php           # Customer support / contact page
├── .htaccess                # URL rewriting and server configuration
│
└── admin/                   # Administrative backend panel
    ├── add_money.php        # Financial management script
    ├── banner.php           # Banner/advertisement management
    ├── category.php         # Food category controls
    ├── coupon_code.php      # Discount and coupon management
    ├── delivery_boy.php     # Delivery personnel management
    ├── dish.php             # Menu item/dish management
    ├── footer.php           # Admin panel footer component
    ├── assets/              # CSS, JS, images, and fonts for admin dashboard
    └── html/                # Dashboard layouts and templates
