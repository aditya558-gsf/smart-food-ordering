# Full Stack Food Ordering Platform (MERN)

A full-stack food ordering web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to explore food items, manage their cart, and place orders through a responsive and user-friendly interface.

---

## Features

* User Authentication (Login / Signup)
* Add to Cart & Remove from Cart
* Dynamic Food Listing
* Order Placement System
* REST API Integration
* Admin Panel for Product & Order Management
* Secure Password Hashing using bcrypt
* JWT-based Authentication

---

## Tech Stack

* **Frontend:** React.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** JWT
* **Payment (optional):** Stripe

---

## Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/aditya558-gsf/smart-food-ordering.git
cd smart-food-ordering
```

---

### 2. Install dependencies

```bash
cd frontend
npm install

cd ../backend
npm install

cd ../admin
npm install
```

---

### 3. Setup Environment Variables

Create a `.env` file inside the **backend** folder:

```env
JWT_SECRET=your_secret_key
SALT=10
MONGO_URL=your_mongodb_connection
STRIPE_SECRET_KEY=dummy_key
```

> Never upload your `.env` file to GitHub.

---

### 4. Run the project

```bash
# Start Backend
cd backend
node server.js

# Start Frontend
cd frontend
npm run dev
```

---

## Deployment

This project can be deployed using platforms like **Render**, **Vercel**, or **Netlify**.

---

## Future Improvements

* Online payment integration
* Order tracking system
* Enhanced UI/UX
* Real-time notifications

---

## Author

**Aditya Kumar Das**

---

## Note

This project was developed to practice full-stack development and demonstrates integration of frontend, backend, and database systems in a real-world application.
