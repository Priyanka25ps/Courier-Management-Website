# 📦 Courier Management System  

A web-based **Courier Management System** developed using HTML, CSS, JavaScript, PHP, and MySQL that enables users to book and track couriers while allowing branch managers to manage deliveries and staff efficiently.  

---

## 📌 Introduction  
With the advent of the internet, booking a courier has become a hassle-free task. This system serves as a bridge between **users** and **courier service providers**, allowing:  

✔ **Users to register, book a courier, and track their deliveries.  
✔ **Branch Managers to handle bookings, manage deliveries, update courier statuses, and manage staff members.  
✔ **Staff Members to view assigned deliveries and update the delivery status.  

---

## 🚀 Features  
- **User Registration & Authentication – Secure login and registration.  
- **Courier Booking – Users can book courier services.  
- **Courier Tracking – Users can check the real-time status of booked couriers.  
- **Branch Manager Dashboard – Manage courier deliveries and update statuses.  
- **Staff Management – Branch managers can add or remove staff members.  
- **Delivery Assignment – Managers can assign specific staff for deliveries.  

---

## 🛠️ System Specifications  

###  Software Requirements  
- **Code Editor: Visual Studio Code  
- **Server: XAMPP (Apache Web Server)  
- **Browser: Google Chrome  
- **Operating System: Windows 11  
- **Frameworks/Libraries: Bootstrap  
- **Frontend: HTML, CSS, JavaScript  
- **Backend: PHP  
- **Database: MySQL  

###  Hardware Requirements  
- **Processor: Intel(R) Core (TM) i5-9300H CPU @ 2.40GHz  
- **RAM: 8GB  
- **Architecture: 64-bit operating system, x64-based processor  
- **Input Devices: Keyboard and Mouse (recommended)  


## 📂 Project Structure  
/courier-management 
│── index.php # Home page
│── register.php # User registration
│── login.php # User login
│── dashboard.php # User dashboard
│── manager.php # Branch manager dashboard
│── staff.php # Staff management
│── track.php # Courier tracking
│── db_config.php # Database connection
│── assets/ # CSS, JS, Images
└── README.md # Project documentation


---

## ⚙️ Installation & Setup  

###  Step 1: Clone the Repository  
```sh
git clone https://github.com/your-username/courier-management.git
cd courier-management

Step 2: Set Up the Database
Open XAMPP and start Apache & MySQL.
Create a new database in MySQL.
Import the provided SQL file (database.sql).

Step 3: Configure the Database Connection
Open db_config.php and update the database credentials:
$host = "localhost";
$user = "your-username";
$password = "your-password";
$database = "your-database-name";

Step 4: Run the Project
Start a local server (XAMPP, WAMP, or MAMP).
Open your browser and go to:
http://localhost/courier-management

📌 Usage
Users: Register, log in, book couriers, and track deliveries.
Branch Managers: Manage bookings, assign deliveries, update statuses, and handle staff members.
Staff Members: View assigned deliveries and mark deliveries as completed.

🛠️ Future Enhancements
✔ Email & SMS Notifications – Notify users about courier updates.
✔ Payment Integration – Allow users to pay for courier services online.
✔ Live Location Tracking – Track couriers in real time.

📜 License
This project is open-source and available under the MIT License.

🤝 Contributing
Contributions are welcome! If you find any issues or have feature requests, feel free to open an issue or submit a pull request.



