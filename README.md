# RoadSathi 🚗🛠️

RoadSathi is a web-based smart roadside assistance platform designed to help vehicle owners during emergency situations.

Project Title

RoadSathi – Smart Roadside Assistance Web Application

Project Overview

RoadSathi is a web-based smart roadside assistance application designed to help vehicle owners during emergency situations on the road. The platform allows users to request essential services such as fuel delivery, mechanic assistance, towing services, and vehicle washing through a single, user-friendly interface.

The main objective of this project is to reduce the response time during roadside emergencies and provide a digital solution that connects users with service providers efficiently. The application focuses on simplicity, accessibility, and a modern user experience.

Frontend Description

The frontend of RoadSathi is fully implemented using HTML, CSS, JavaScript, and Bootstrap 5. It provides an interactive and responsive user interface that works smoothly across different devices.

The application starts with a login page, where users enter their email, phone number, and password. Basic form validation is implemented using HTML5 and JavaScript to ensure correct input before proceeding.

After successful login, users are redirected to the service request page. This page allows users to:

Enter their name and current location

Select one roadside service at a time using interactive service cards

Provide additional details based on the selected service

Each service card dynamically expands using JavaScript and Bootstrap collapse components to collect relevant information such as fuel type and quantity, problem description, towing destination, or washing preference.

Custom CSS is used for styling, animations, and visual effects, while JavaScript handles page navigation, form validation, and service selection logic without reloading the page.

Backend Description (Conceptual and Practical Approach)

The backend of RoadSathi is designed conceptually to make the project complete and scalable. Although the current implementation focuses mainly on the frontend, the backend architecture is clearly defined and can be integrated easily.

The backend is proposed using Node.js with Express.js, which handles server-side logic and communication between the frontend and database.

Backend Responsibilities

The backend is responsible for:

User authentication and login validation

Receiving service request data from the frontend

Storing user and service information in the database

Managing service request status

Sending responses back to the frontend

Backend Working Flow

The user submits login details from the frontend

Frontend sends data to backend using REST APIs

Backend validates the user credentials

User selects a roadside service and submits the request

Backend receives the service request data

Data is stored in the database

Backend updates service request status

Response is sent back to the frontend

Backend Technologies Used

Node.js – Server-side runtime environment

Express.js – Backend framework for handling routes and APIs

MongoDB – NoSQL database for storing user and service data

RESTful APIs – For frontend–backend communication

JWT / Basic Authentication – For secure login (conceptual)

Cloud Server (AWS / Render) – For deployment (conceptual)

Backend File Structure (Proposed)
RoadSathi/
│
├── index.html        (Frontend UI)
├── style.css         (Styling)
├── script.js         (Frontend logic)
│
├── server.js         (Backend server)
├── package.json      (Backend configuration)


Backend files are saved with the .js extension and run using Node.js.

---

## 🚀 Features
- Fuel delivery request
- Mechanic assistance
- Towing service
- Simple and user-friendly interface

---

## 🛠️ Tech Stack
**Frontend:** HTML, CSS, JavaScript, Bootstrap 5 
**Backend:** Node.js, Express.js
**Database:** MongoDB  
**Authentication:** Firebase Authentication (phone OTP)
**Payment:** Razorpay
**Maps:** Google Maps (for location and tracking)

---

## 🌐 Live Links
**Frontend:** https://github.com/DevKumarofficial/RoadSathi/  
**Backend:** (will add Render link here)

---

## 👩‍💻 Authors
Dev Kumar Gupta  
Vanshika Malani
