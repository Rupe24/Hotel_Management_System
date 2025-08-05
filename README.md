📌 ABOUT THE PROJECT

The Hotel Management System is a simple web-based project developed using PHP and MySQL. 
The frontend is built with HTML, CSS, JavaScript (jQuery & AJAX), and Bootstrap, using a free template from StartBootstrap – Creative.
This system is designed to simplify hotel operations, including room booking, check-in, and check-out processes. It allows hotel management to store room data, including categories and daily pricing, and track room availability dynamically.

The system provides two main interfaces:

1. Admin Side – for hotel staff to manage rooms, bookings, settings, and guest check-ins/outs.
2. Guest Side – for users to browse available rooms, view hotel information, and make bookings.

🧩 Features

🔐 Admin Side:

1. Category Page – Manage the list of room categories.
2. Rooms Page – Manage hotel rooms and their details.
3. Settings Page – Configure the system title, images, and about content.
4. Check-in Page – Manage guest check-in details.
5. Checkout Page – Edit check-in details and process check-outs.
6. Booked Page – View and confirm guest bookings.

👤 Guest Side:

1. Home Page – Landing page for guests visiting the system.
2. Rooms Page – Displays available rooms based on selected dates.
3. About Page – Shows information about the hotel.

🔑 Default Admin Access: To log in to the admin panel, use the following credentials:

1. Username: admin
2. Password: admin123


🚀 HOW TO RUN/INSTALL:

Follow these steps to set up and run the Hotel Management System on your local machine:

1. Download the Project : Click the green Code button on this repository.Select "Download ZIP", then extract the folder.(Or clone the repo using Git if you prefer.)

2️. Set Up a Local Web Server : Install XAMPP (or WAMP/Laragon) — any server that supports PHP & MySQL. After installing, open XAMPP Control Panel and start: Apache and MySQL

3️. Create a Database : Open your browser and go to http://localhost/phpmyadmin. Click on "New", and create a database named:hotel_db
  
4. Import the SQL File : Inside the project folder, locate the database/folder. Inside it, find the .sql file (example: hotel_db.sql). In phpMyAdmin: Open the hotel_db database.
   Click on the "Import" tab. Choose the .sql file and click Go.

5️. Move the Project to XAMPP Folder. Copy the entire project folder. Paste it inside: C:\xampp\htdocs\ 
   Example path: C:\xampp\htdocs\hotel-management-system\

6️. Run the Project in Your Browser. For the Guest Side, open: http://localhost/hotel-management-system/. For the Admin Panel, open: http://localhost/hotel-management-system/admin/
