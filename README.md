# Web App with MongoDB Backend

### Project Overview

Developed a full-stack web application for property booking with seamless MongoDB integration to manage user data, property listings, and booking records. The application supports user authentication, property search and filtering, real-time availability checks, and booking confirmations. Built using modern web technologies, it ensures a responsive user experience while maintaining data consistency and scalability through efficient database operations.

---

## Access to Code 🔒

The source code for this project is **private** and available upon request.

If you're an **employer** or **recruiter** and would like to review the code, please **request access via email** at **ayanhashmi205@yahoo.com**.

---

## Installation 📦

#### Clone this repo

```bash
git clone https://github.com/ayanhashmi/airbnb-booking-app.git
cd airbnb-booking-app
```

#### Install dependencies

```bash
npm install
```

#### Start the application

```bash
node server.js
```

Navigate to `http://localhost:3000` in your browser

---

## Features 📋

* Property search and filtering by location, type, and bedrooms
* Interactive property listings with detailed information
* Complete booking system with client information capture
* MongoDB Atlas integration for data persistence
* Responsive web interface with clean UI design
* RESTful API endpoints for CRUD operations
* Real-time property availability checking
* Booking confirmation system with email notifications

---

## Technology Stack 🔧

### Backend
* **Node.js** - Runtime environment
* **Express.js** - Web application framework
* **MongoDB** - NoSQL database (MongoDB Atlas)
* **Mongoose** - MongoDB object modeling

### Frontend
* **HTML5** - Markup language
* **CSS3** - Styling and responsive design
* **JavaScript** - Client-side interactivity
* **Bootstrap** - CSS framework for responsive design

---

## Database Schema 📊

### Extended Data Model

The application extends the sample_airbnb database with a custom booking collection:

#### Bookings Collection
```javascript
{
  listing_id: ObjectId,
  client_name: String,
  email: String,
  phone_day: String,
  phone_mobile: String,
  postal_address: String,
  home_address: String,
  booking_start: Date,
  booking_end: Date,
  created_at: Date
}
```

---

## API Endpoints 🛠️

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/listings` | Get filtered property listings |
| GET | `/api/listings/:id` | Get specific property details |
| POST | `/api/bookings` | Create new booking |
| GET | `/api/bookings/:listing_id` | Get bookings for property |

---

## Author ✨

| <a href="https://github.com/ayan9870" target="_blank">**Muhammad Ayan Hashmi**</a> |
|:--:|
| ![Ayan Hashmi](https://github.com/ayan9870.png?size=100) |
| [`github.com/ayan9870`](https://github.com/ayan9870) |

---

## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
