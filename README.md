# Travel Booking System

A full-stack travel booking platform that enables users to search and book **buses, trains, and flights** through a single application.  
The project is built using **Django**, **Django REST Framework**, and **Python** for the backend, while the frontend is developed using **React.js**, **HTML**, **CSS**, and **JavaScript**.

---

# Features

## ✈ Flight Booking Module
- Search available flights
- View flight schedules and details
- Ticket booking system
- Passenger information management

## 🚆 Train Booking Module
- Search trains between locations
- View train timings and availability
- Reservation and booking management

## 🚌 Bus Booking Module
- Browse bus routes and schedules
- View seat availability
- Book bus tickets

## 👤 User Features
- User registration and login
- JWT/Session-based authentication
- Booking history tracking
- Responsive and interactive UI

## 🛠 Admin Features
- Manage buses, trains, and flights
- Add/update/delete schedules
- Monitor bookings and users
- Manage transport data through Django Admin

---

# Tech Stack

## Backend
- Python
- Django
- Django REST Framework (DRF)
- SQLite / MySQL

## Frontend
- React.js
- HTML5
- CSS3
- JavaScript

## Tools & Libraries
- REST APIs
- Axios / Fetch API
- Git & GitHub

---

# System Architecture

```text
React Frontend  <---- REST APIs ---->  Django Backend  <----> Database
```

---

# Project Structure

```bash
travel-booking-system/
│
├── backend/
│   ├── manage.py
│   ├── booking/
│   ├── bus/
│   ├── train/
│   ├── flight/
│   ├── api/
│   └── requirements.txt
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
└── README.md
```

---

# Installation and Setup

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/travel-booking-system.git
cd travel-booking-system
```

---

# Backend Setup (Django + DRF)

## 2. Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3. Install Backend Dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

## 5. Start Django Server

```bash
python manage.py runserver
```

Backend will run on:

```text
http://127.0.0.1:8000/
```

---

# Frontend Setup (React)

## 6. Move to Frontend Directory

```bash
cd frontend
```

---

## 7. Install Frontend Dependencies

```bash
npm install
```

---

## 8. Start React Development Server

```bash
npm start
```

Frontend will run on:

```text
http://localhost:3000/
```

---

# API Endpoints

| Endpoint | Description |
|---|---|
| `/api/bus/` | Bus booking APIs |
| `/api/train/` | Train booking APIs |
| `/api/flight/` | Flight booking APIs |
| `/api/auth/` | Authentication APIs |

---

# Modules Overview

| Module | Functionality |
|---|---|
| Bus Module | Bus search and ticket booking |
| Train Module | Train schedules and reservations |
| Flight Module | Flight booking management |
| Authentication | User login and registration |
| REST API | Frontend-backend communication |
| Admin Dashboard | Data and booking management |

---

# Future Enhancements

- Online payment gateway integration
- Real-time seat availability
- Email/SMS notifications
- AI-based travel recommendations
- Live tracking system
- Mobile application support

---

# Learning Outcomes

This project helped in understanding:
- REST API development using Django REST Framework
- Frontend-backend integration using React and APIs
- Authentication and authorization
- Database operations and model relationships
- Full-stack web application development
- State management and API handling in React

---

# Contributors

- Your Name
- Team Members (if any)

---

# License

This project is developed for educational and learning purposes.
