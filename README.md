## QuickCuisine
QuickCuisine is an online food ordering system designed for easy access by Admins, Customers, and Vendors. Admins manage menus, promotions, and view sales reports; Customers browse menus, customize orders, make secure payments, and track status; Vendors handle incoming orders to ensure smooth service. It’s simple, efficient, and convenient..

### Online Food Ordering System
### Introduction
The Online Food Ordering System is designed to simplify food ordering for customers and streamline operations for restaurants. Customers can browse menus, place orders, and make payments securely online.

### Features
- Easy online ordering from a mobile-friendly interface.
- Multiple payment options (debit/credit card, digital wallets, etc.).
- Real-time order tracking for users and restaurant staff.
- Order queue management for efficient processing.
- Admin panel to manage food items, vendors, and orders.

### Screenshots
Include screenshots of the application interface:
- **Home Page**
- **Menu Page**
- **Order Tracking**
- **Admin Dashboard**

### Installation
1. **Install XAMPP**: XAMPP provides Apache, PHP, and MySQL needed for the project.
2. **Database Setup**:
   - Open MySQL and import the database from `/db/DB_FOOD.sql`.
3. **Configure Files**:
   - Modify `config.php` with your database credentials.
4. **Start the Application**:
   - Run Apache and MySQL servers in XAMPP.
   - Access the application at `http://localhost/yourprojectfolder`.

### Usage
1. **Customer**: Browse food items, add to cart, and proceed with checkout.
2. **Admin**: Log in to manage vendors, orders, and menu items.
3. **Vendor**: Update menu and order statuses for customers.

### Project Structure
Online-Food-Ordering-System/ ├── src/ │ ├── index.php │ ├── order.php │ └── ... ├── db/ │ └── DB_FOOD.sql ├── assets/ │ ├── images/ │ └── css/ ├── docs/ │ └── Documentation.pdf ├── tests/ │ └── test_cases.md ├── README.md └── LICENSE

### Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Development Environment**: XAMPP

### Database Schema
The database schema includes tables for customers, orders, vendors, and menu items. Primary tables are:
- `tblcustomers`
- `tblorders`
- `tblvendors`
- `tblmenu`

Refer to `/docs/Documentation.pdf` for detailed ER diagrams and data flow diagrams.

### Future Enhancements
- Add delivery time estimation feature.
- Implement push notifications for real-time order updates.
- Integrate third-party payment gateways for more options.

### Contributing
To contribute to this project:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

### License
This project is licensed under the MIT License.
