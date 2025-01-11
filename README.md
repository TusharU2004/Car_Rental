# 🚗 Car Rental System  

The **Car Rental System** is a robust web-based platform designed to streamline car rental operations for users and administrators. The system provides an intuitive interface for users to book vehicles and make payments, while administrators can manage car listings, monitor earnings, and oversee operations seamlessly.  

---

## 📋 Features  

### **User Module**  
- **Car Booking**  
  - Search for cars, check availability, and book vehicles.  
  - Flexible booking options: hourly or daily rentals.  
  - Dynamic cost calculation based on the selected booking duration.  

- **Payment Integration**  
  - Secure online payments using a reliable gateway.  
  - Payment receipts are generated for every transaction and can be downloaded by users.  

- **Booking Receipt**  
  - Detailed receipts include booking information, car details, rental period, total cost, and payment confirmation.  

- **Email Notifications**  
  - Automated email alerts for booking status updates (approval or rejection).  

---

### **Admin Module**  
- **Car Listing Management**  
  - Review, approve, or reject car listing requests submitted by car owners.  
  - Approved cars become available for user bookings.  

- **Bulk Approval/Rejection**  
  - Approve or reject multiple car listing requests in one go.  
  - Sends email notifications to all relevant users automatically.  

- **Graphical Reports of Earnings**  
  - Interactive graphs display earnings filtered by date range or car models.  
  - Uses Chart.js for dynamic visualizations.  

- **Booking and Payment Management**  
  - Admins can manage all bookings and monitor payment records.  

---

## ⚙️ Technology Stack  

### **Frontend**  
- HTML, CSS , JavaScript, Bootstrap.  

### **Backend**  
- PHP for server-side logic.  
- MySQL for database management.  

### **Libraries & Integrations**  
- **PHPMailer**: For email notifications.  
- **Chart.js**: For rendering graphical earnings reports.  
- **Payment Gateway**: Secure online payment processing.  

---

## 🔧 Setup Instructions  

### **1. Set Up the Database**  
1. Create a new database named `car_rental`.  
2. Import the `car_rental.sql` file into the database.  

### **2. Configure the Database Connection**  
Update the `includes/config.php` file with your database credentials:  

### **3. Install Dependencies**
Ensure your server supports:

PHP 7.4 or later.
PHPMailer Installation
```bash
composer require phpmailer/phpmailer
```
Chart.js
Download and include the Chart.js library from Chart.js Official Site.

### **4.Run the Application**
   - **For a local server:**  
     - Place the project folder in the server’s root directory (e.g., htdocs for XAMPP).
     - Access the project at http://localhost/Car-Rental-System/.
   - **For a web server:** 
     - Upload the project files to the web server.
     - Configure config.php for production credentials.

## 🚀 How It Works
   - **User Flow**
     - Register/Login.
     - Search for cars.
     - Book a vehicle.
     - Pay online.
     - Download the receipt.
  
   - **Admin Flow**
     - Review car listing requests.
     - Approve/Reject requests (bulk action supported).
     - Monitor bookings and payments.
     - View earnings reports.

## 📈 Project Highlights
  - Real-time Booking System: Ensures cars are available before booking.
  - Dynamic Payment Calculation: Supports hourly and daily rental rates.
  - Bulk Action Capability: Simplifies admin tasks with multi-select approval/rejection.
  - Earnings Reports: Interactive, date-filtered graphs for better financial insights.

For admin and user password mail at umretiya123@gmail.com
