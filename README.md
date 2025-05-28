<h1>Car Rental Website | A Car Rental System using PHP & MYSQL</h1>
<h2>Car Rental Online Reservations</h2>
<p>
Car Rental Website using PHP and Mysql, HTML, CSS, JS, VUE JS.
The website has two sides; 1- The client-side and 2- The admin side.
1- for the client-side, the user or the client can reserve a car by selecting the pickup and return date then the user will get a collection of cars that are available during the selected time, and finally, the user has to enter his details, and then the reservations will be created successfully.
2- for the admin side, the admin can manage reservations and manage cars, car brands, and car types (Create, Read, Update, Delete)	
</p>
<hr>
<div>
	<h3>Technologies</h3>
  	<ul>
		<li>HTML & CSS</li>
		<li>Bootstrap</li>
		<li>JavaScript & Jquery & VUE JS</li>
		<li>PHP & MYSQL</li>
	</ul>
</div>
<hr>
<div>
	<h3>Website DEMO</h3>
  	
	<p>
		Username: admin
		<br>
		Password: 123456789
	</p>
</div>
<hr>
<div>
	<h3>Installation</h3>
  	<ol>
		<li>Download the files + database file (.sql)</li>
		<li>Create new database with the name "car_rental" and then Import the sql file downloaded </li>
		<li>Check the files connect.php to make sure that everything is working</li>
		<li>The website is ready to use</li>
		<li>Feel free to edit the missig parts or the existing parts</li>
	</ol>
</div>

# 🚗 Rent-a-Car Management System

The **Rent-a-Car Management System** is a full-stack web application developed as part of a Database Management System (DBMS) semester project. It is designed to manage the operations of a car rental business, allowing staff to add, update, delete, and view details of vehicles, customers, and bookings through a simple HTML + PHP-based interface, fully connected with a MySQL backend.

---

## 📌 Features

- ✅ Add, update, delete, and view:
  - 🚘 Vehicle information
  - 👤 Customer details
  - 📆 Booking records
- ✅ Easy-to-use HTML forms
- ✅ PHP scripts for CRUD operations using `mysqli`
- ✅ MySQL database with relational structure
- ✅ ER Diagram, schema, and SQL dump included
- ✅ Scalable for basic enhancements like search or filtering

---

## 🧱 Tech Stack

- **Front-end:** HTML5
- **Back-end:** PHP
- **Database:** MySQL (phpMyAdmin)
- **Local Server:** XAMPP

---

## 🗂️ Project Structure

📁 rentacar/
├── index.html → Homepage or dashboard
├── db.php → MySQL database connection file
├── vehicle.php → Vehicle management (CRUD)
├── customer.php → Customer management (CRUD)
├── booking.php → Booking management (CRUD)
└── rentacar.sql → Database schema and sample data


---

## ⚙️ How to Run Locally

1. **Start XAMPP:**
   - Open XAMPP Control Panel
   - Start **Apache** and **MySQL**

2. **Database Setup:**
   - Go to `http://localhost/phpmyadmin`
   - Create a new database (e.g., `rentacar`)
   - Import the `rentacar.sql` file into it

3. **File Setup:**
   - Copy all project files into `C:/xampp/htdocs/rentacar/`

4. **Run Project:**
   - Open your browser and go to `http://localhost/rentacar/index.html`
   - Use the forms to add/edit/delete/view data

---

## 📊 Database Overview

- `vehicles` — Vehicle ID, Model, Type, Status, Price
- `customers` — Customer ID, Name, Email, Contact, CNIC
- `bookings` — Booking ID, Customer ID, Vehicle ID, Start Date, End Date, Status

All tables are connected using **foreign keys** to maintain data integrity.

---

## 📚 Academic Context

This project was built for a university-level **DBMS course**. It demonstrates:
- Proper database design using ER modeling
- SQL query writing
- Full implementation of CRUD operations
- Integration of front-end and back-end with real-time database interaction

---

## 🏁 Future Enhancements (Optional)

- Search and filter functionality
- Authentication system for admin login
- Booking conflict checks
- Return date validation and pricing automation

---

## 🧾 License

This project is for **educational use only** and is not intended for production deployment.

---

## 🙌 Acknowledgment

Developed as a semester project by students of **Bahria University – BSAI 2A**.
