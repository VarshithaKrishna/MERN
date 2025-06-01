
# 🏡 Dream Nest – MERN Stack Property Rental Platform

Dream Nest is a modern full-stack web application designed to simplify the rental and booking experience. With a responsive UI and robust backend, it offers seamless functionality for both **property owners (hosts)** and **renters (guests)**.

---

## 📘 Abstract

Dream Nest bridges the gap between property owners and renters by offering:

- 🔐 Secure authentication using **JWT**
- 🏘️ Property listing, filtering, and image uploads
- 📅 Property booking and tracking
- 📤 Host dashboard to manage properties
- 🔎 Full-featured frontend using **React**

Built with the **MERN Stack**:
> MongoDB • Express.js • React.js • Node.js

---

## 🖥️ Project Preview

Here are real screenshots from Dream Nest in action:

### 🔑 Login & Registration
<img src="screenshots/Screenshot 2025-06-01 182731.png" width="600"/>

<img src="screenshots/Screenshot 2025-06-01 182740.png" width="600"/>

---

### 🏘️ Home & Listings View
<img src="screenshots/Screenshot 2025-06-01 181157.png" width="600"/>

---

### 📋 Listing Details
<img src="screenshots/Screenshot 2025-06-01 181211.png" width="600"/>

---

### ❤️ Wishlist
<img src="screenshots/Screenshot 2025-06-01 181436.png" width="600"/>

---

### 📅 Booking History/ Reservation History
<img src="screenshots/Screenshot 2025-06-01 185954.png" width="600"/>

---

### 📱 Responsive Design
<img src="screenshots/Screenshot 2025-06-01 181315.png" width="600"/>

---
### 🏠 Hosted Places by Host
<img src="screenshots/Screenshot 2025-06-01 181504.png" width="600"/>

<img src="screenshots/Screenshot 2025-06-01 181515.png" width="600"/>


---

## 📦 Installation

```bash
git clone https://github.com/yourusername/dream-nest.git
cd dream-nest

# Backend
cd server
npm install
node index.js

# Frontend
cd ../client
npm install
npm start
````

---

## 🔐 Environment Variables

Create a `.env` file in the `/server` folder:

```env
PORT=5000
MONGODB_URI=your-mongo-uri
JWT_SECRET=your-secret-key
```

---

## 🧪 API Overview

| Method | Endpoint                    | Description            |
| ------ | --------------------------- | ---------------------- |
| POST   | /auth/register              | Register new user      |
| POST   | /auth/login                 | Login & receive JWT    |
| GET    | /properties                 | List all properties    |
| POST   | /properties                 | Add new property       |
| GET    | /bookings/\:userId          | View bookings for user |
| POST   | /bookings                   | Book a property        |
| PATCH  | /users/\:userId/\:listingId | Toggle wishlist        |

---

## 🔧 Tech Stack

* **Frontend**: React.js, Redux, Sass
* **Backend**: Node.js, Express.js
* **Database**: MongoDB (with Mongoose)
* **Authentication**: JWT + Bcrypt
* **Image Upload**: Multer (stored in `/public/uploads`)
* **Tools**: Postman, VS Code, Git

---

## 💡 Features

* ✅ Register/Login functionality
* 🧳 Browse & book properties
* 🏡 Host panel to upload listings
* 🖼️ Image upload and display
* 🔒 Secure access with token-based auth
* 📱 Fully responsive across devices

---

## 🔮 Future Enhancements

* 💳 Stripe payment integration
* 🗺️ Google Maps for geo search
* 📬 Email & SMS booking notifications
* 📊 Admin analytics dashboard
* 📲 Mobile application

---

