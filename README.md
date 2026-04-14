# Smart Food Ordering Platform

This project is a full-stack food delivery web application developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). It provides a user-friendly interface for browsing food items, managing cart, and placing orders efficiently.

---

## Features

* User Authentication (Login / Signup)
* Add to Cart & Remove from Cart
* Dynamic Food Listing
* Order Placement System
* REST API Integration
* Admin Panel for Product & Order Management
* Secure Password Hashing (bcrypt)
* JWT-based Authentication

---

## Tech Stack

* Frontend: React.js
* Backend: Node.js, Express.js
* Database: MongoDB
* Authentication: JWT
* Payment (optional): Stripe

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

Create a `.env` file inside the backend folder:

```env
JWT_SECRET=your_secret_key
SALT=10
MONGO_URL=your_mongodb_connection
STRIPE_SECRET_KEY=dummy_key
```

---

### 4. Start the project

```bash
# Start Backend
cd backend
node server.js

# Start Frontend
cd frontend
npm run dev
```

---

---

## Author

Aditya Kumar Das

---

## Note

This project was built for learning full-stack development and demonstrates integration of frontend, backend, and database systems.
