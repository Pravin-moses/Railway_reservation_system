# Railway Reservation System

A comprehensive full-stack web application designed to manage railway ticket reservations online. The system includes features for both **users** (to book and manage tickets) and **admins** (to handle train schedules and reservation data).

This project is built using **HTML**, **CSS**, and **JavaScript** for the frontend, and **Node.js**, **Express.js**, and **MongoDB** for the backend and data storage.

---

##  Project Description

The Railway Reservation System simulates an online platform for train ticket booking and management. Users can register, search trains, book tickets, and view bookings. Admins can manage train data, schedules, and view user bookings.

---

##  Features

###  User Panel
- User Registration & Login
- Search Trains by Routes
- Book Train Tickets
- View Active & Past Bookings
- Cancel Booked Tickets

###  Admin Panel
- Admin Login
- Add, Edit, Delete Train Details
- View All Bookings
- Manage User Data

---

##  Technologies Used

### Frontend
- HTML5  
- CSS3  
- JavaScript (Vanilla JS)

### Backend
- Node.js  
- Express.js

### Database
- MongoDB (with Mongoose)

---

##  Project Setup

Follow these steps to set up the project locally:

1. **Clone the Repository**  
   Download or clone this repository to your local machine.

2. **Install Dependencies**  
   Use `npm install` to install required backend packages.

3. **Configure MongoDB**  
   Set up MongoDB locally or via cloud (e.g., MongoDB Atlas) and provide the URI in a `.env` file.

4. **Start the Server**  
   Run the server using `node server.js` or `nodemon`.

5. **Access the Application**  
   Open your browser and visit `http://localhost:3000`.

---

##  Folder Structure
railway-reservation-system/
├── public/ → Frontend files (HTML, CSS, JS)
├── routes/ → Route definitions for user/admin
├── models/ → MongoDB schemas (User, Train, Booking)
├── views/ → (Optional template engine views)
├── server.js → Main backend server file
├── .env → Environment variables (DB URI)
└── package.json → Project configuration and scripts

---

##  Screenshots
1.Homepage

![image](https://github.com/user-attachments/assets/d32bb563-3f82-48e5-ae52-624f1b10dcec)


2.Admin Login

![image](https://github.com/user-attachments/assets/9b447fd0-7924-4786-8bb4-e5874f346c22)


3.Admin Dashboard
![image](https://github.com/user-attachments/assets/4db3e930-4b04-4964-b77c-7f28bcc1879c)

4.Train Search
![image](https://github.com/user-attachments/assets/e7428303-a94e-43b1-9a0f-fccbad5559ed)

5.Availiable Trains
![image](https://github.com/user-attachments/assets/f25840f2-b49e-4d41-914e-158d34acc413)

6.Payment Gateway
![image](https://github.com/user-attachments/assets/021c707e-1ef8-488f-93ed-c83996df689c)

7.Ticket Details
![image](https://github.com/user-attachments/assets/0f5505e3-892b-4f50-965e-51c0e48de6a4)

8.Backend 

![image](https://github.com/user-attachments/assets/cbbdcfae-a825-49e7-990c-5fae8978ac03)

---

##  Future Enhancements

- JWT Authentication
- Payment Gateway Integration
- Email/SMS Notifications
- PDF Ticket Download
- Real-Time Seat Availability

---


##  Acknowledgements

This project is developed as part of a mini project for academic purposes.

