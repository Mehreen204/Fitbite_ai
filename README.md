# 🍎 FitBite AI – Smart Fitness & Nutrition Tracker

> **FitBite AI** is a modern full-stack MERN fitness and nutrition tracking application designed to help users build healthier habits through intelligent meal logging, calorie tracking, hydration monitoring, activity tracking, and personalized fitness goals. The application combines an elegant UI with a scalable backend architecture to deliver a seamless health management experience.

---

## 🌟 Overview

FitBite AI enables users to monitor their daily nutrition and fitness journey from a single dashboard. Users can register securely, log meals, track calories and macronutrients, monitor water intake and weight progress, and visualize their health data in real time.

The project is built using the **MERN Stack (MongoDB, Express.js, Node.js)** with a responsive frontend and enterprise-level backend architecture.

---

# ✨ Features

### 🔐 User Authentication

* Secure user registration and login
* JWT Authentication
* Password hashing using Bcrypt
* Protected API routes
* User profile management

---

### 🍽️ Nutrition Tracking

* Search foods from the food database
* Add foods to Breakfast, Lunch, Dinner, or Snacks
* Automatic calorie calculation
* Macronutrient tracking
* Daily nutrition summary

---

### 🥗 Food Database

* MongoDB-powered food collection
* Nutrition information for each food
* Verified foods
* Easily expandable with thousands of food items

---

### 💧 Water Tracking

* Daily water intake logging
* Progress toward hydration goals
* Historical water logs

---

### ⚖️ Weight Tracking

* Weight history
* BMI calculation
* Body fat tracking (optional)
* Progress monitoring

---

### 🏃 Activity Tracking

* Daily steps
* Calories burned
* Workout duration
* Distance tracking
* Activity history

---

### 🎯 Goal Management

* Personalized calorie goals
* Protein goals
* Carbohydrate goals
* Fat goals
* Weight goals
* Goal progress tracking

---

### 🔔 Smart Notifications

* Meal reminders
* Water reminders
* Workout reminders
* Achievement notifications
* Weekly reports

---

### 📊 Dashboard

* Dynamic statistics
* Calories consumed
* Calories remaining
* Macronutrient charts
* Daily progress
* Activity overview
* Goal progress

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)
* Axios
* Lucide Icons

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose

### Authentication

* JWT
* BcryptJS

### Security

* Helmet
* CORS
* Cookie Parser
* Express Validator

### Development Tools

* Nodemon
* Git
* GitHub

---



# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/FitBite-AI.git
```

```bash
cd FitBite-AI
```

---

## Install Dependencies

```bash
npm install
```

---

## Configure Environment Variables

Create a `.env` file in the project root.

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

JWT_EXPIRE=7d
```

---

## Seed Food Database

```bash
npm run seed
```

---

## Start Development Server

```bash
npm run dev
```

Backend runs on:

```text
http://localhost:5000
```

---

# 🔗 API Endpoints

## Authentication

```http
POST /api/auth/register
```

```http
POST /api/auth/login
```

```http
GET /api/auth/profile
```

---

## Foods

```http
GET /api/foods
```

```http
GET /api/foods/:id
```

```http
POST /api/foods
```

```http
PUT /api/foods/:id
```

```http
DELETE /api/foods/:id
```

---

## Meals

```http
GET /api/meals
```

```http
POST /api/meals
```

```http
PUT /api/meals/:id
```

```http
DELETE /api/meals/:id
```

---

## Users

```http
GET /api/users/profile
```

```http
PUT /api/users/profile
```

---

# 📷 Screens

* Landing Page
* Login
* Register
* Dashboard
* Meal Logger
* Activity Tracker
* Water Tracker
* Weight Progress
* Profile
* Goal Settings

---

# 🔒 Security Features

* Password Hashing
* JWT Authentication
* Protected Routes
* Environment Variables
* Input Validation
* Secure HTTP Headers
* CORS Protection

---

# 📈 Future Improvements

* 🤖 AI-powered meal recommendations
* 📷 Food image recognition
* 🧠 AI nutrition chatbot
* 📱 Progressive Web App (PWA)
* 🌙 Dark/Light themes
* 📊 Weekly and monthly analytics
* 📅 Meal planning calendar
* 🥗 Custom recipes
* 🏆 Achievement badges
* 👥 Social challenges and leaderboards
* 📱 Mobile app (React Native)

---

# 💡 Learning Outcomes

This project demonstrates practical experience with:

* Full-Stack MERN Development
* REST API Design
* MongoDB Data Modeling
* Authentication & Authorization
* MVC Architecture
* CRUD Operations
* Dashboard Development
* Nutrition Data Management
* Secure Backend Development
* Responsive UI Design
* Git & GitHub Workflow

---

# 👩‍💻 Author

**Mehreen Fatima**

# 📄 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub. Feedback, suggestions, and contributions are always welcome!
