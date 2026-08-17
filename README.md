# Medi House

A web-based pharmacy management system built with PHP, MySQL, HTML, CSS, and JavaScript. Patients/customers can browse and order medicines, raise queries, and manage a cart, while admins manage inventory, orders, and sales.

## About

Medi House is an online pharmacy platform where customers can search for drugs, add them to a cart, and place orders, along with submitting queries to the admin/support team. On the admin side, the system supports full inventory control (upload, update, delete items), order/item status management, and sales reporting.

## Features

### Customer / Patient
- Register & login
- Browse and search available drugs/medicines
- Add to cart & place orders
- Submit customer queries (e.g., support/contact requests)
- View order status / history

### Admin
- Secure admin login
- Upload new drug/item listings (with details like price, stock, category)
- Full CRUD on inventory (Create, Read, Update, Delete items)
- Update order/item status (e.g., Pending → Processed → Delivered)
- View and respond to customer queries
- Sales report generation (view total sales, order history, revenue)

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- 
## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Sudeep-B-2112/medi-house.git
   ```
2. Move the project folder into your local server directory (e.g., `htdocs` for XAMPP)
3. Start Apache and MySQL via XAMPP/WAMP
4. Import the database
   - Open phpMyAdmin
   - Create a database named `medi_house`
   - Import the `.sql` file from the `/database` folder
5. Update database credentials in your config file (e.g., `config.php` / `db.php`)
   ```php
   $host = "localhost";
   $user = "root";
   $password = "";
   $dbname = "medi_house";
   ```
6. Open in browser: `http://localhost/medi-house`

## Usage

- **Customer:** Register/login → browse drugs → add to cart → checkout → track order status → raise queries if needed
- **Admin:** Login → upload/manage inventory (CRUD) → update order status → view customer queries → generate sales reports



## Future Improvements

- Online payment gateway integration
- Prescription upload for prescription-only drugs
- Email/SMS order notifications
- Responsive mobile UI
- Low-stock alerts for admin

## Author

**Sudeep B**
GitHub: [@Sudeep-B-2112](https://github.com/Sudeep-B-2112)

