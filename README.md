Project Title

HealSphere – Hospital Management System (Admin Side)

Description

HealSphere is a web-based hospital management system designed to simplify administrative operations for hospital staff. The admin panel enables management of appointments, patients, doctors, and departments efficiently, while providing automated communication for better patient experience.

This project demonstrates the use of Java Spring Boot, Hibernate, MySQL, ReactJS, and JavaScript to build a scalable, maintainable, and interactive application.

Features

CRUD Operations for Appointments

Implemented Create, Read, Update, Delete operations for hospital appointments using Spring Boot and Hibernate.

Ensures smooth data management and supports future scalability.

Allows administrators to manage appointments efficiently in large datasets.

Search & Filtering Functionality

Admins can search appointments by date, doctor, or department.

Improves productivity and reduces manual effort in retrieving specific appointments.

Built using Spring Data JPA queries and REST APIs integrated with the ReactJS frontend.

Automated Email Notifications

Sends email confirmations automatically when an appointment is booked using JavaMail API.

Enhances patient communication and overall experience.

Reduces manual administrative tasks related to notifications.

Technology Stack

Backend: Java, Spring Boot, Hibernate, JavaMail API

Frontend: ReactJS, JavaScript

Database: MySQL

Others: RESTful APIs, Maven (for dependency management)

How It Works

Admin Panel Login: Secure login for hospital administrators.

Appointment Management: Admins can create, update, or delete appointments.

Search & Filter: Quickly retrieve appointments by specifying date, doctor, or department.

Email Notifications: Automatically sends confirmation emails when an appointment is created.

Why This Project is Useful

Reduces manual workload for hospital staff.

Improves appointment scheduling efficiency.

Enhances patient experience with automated notifications.

Provides a scalable and maintainable architecture for future expansion.

Setup Instructions (Optional)

Clone the repository:

git clone https://github.com/your-username/HealSphere.git


Navigate to backend directory and install dependencies using Maven:

cd HealSphere/backend
mvn clean install


Configure MySQL database credentials in application.properties.

Run Spring Boot server:

mvn spring-boot:run


Navigate to frontend directory and start React app:

cd HealSphere/frontend
npm install
npm start


Open http://localhost:3000 in your browser to access the admin panel.

Detailed Explanation

CRUD Operations:
Each operation (Create, Read, Update, Delete) allows the admin to manage appointments efficiently. Using Spring Boot ensures that backend logic is modular, and Hibernate ORM maps Java objects to MySQL tables seamlessly.

Search & Filter:
Instead of manually scanning through all appointments, the admin can quickly find relevant data. This is implemented using dynamic queries in Spring Data JPA and connected to the frontend via REST endpoints.

Automated Emails:
JavaMail API sends confirmation emails as soon as an appointment is booked. This eliminates the need for manual communication, improving hospital efficiency and patient satisfaction.

Frontend Integration:
ReactJS dynamically displays appointment data retrieved from the backend, providing a responsive and interactive user experience. JavaScript handles the UI logic like filtering, sorting, and live updates.
