# 💰 AI Expense Tracking Agent

<div align="center">

![React](https://img.shields.io/badge/React-19-blue?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Express-green?logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-green?logo=mongodb)
![OpenAI](https://img.shields.io/badge/OpenAI-AI-black?logo=openai)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-4-38BDF8?logo=tailwindcss)
![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript)
![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker)

### 🚀 AI-Powered Personal Finance Management Platform

Track expenses • AI Insights • Receipt OCR • Voice Entry • Budget Planning • Smart Reports

</div>

---

# 📌 Overview

AI Expense Tracking Agent is a modern full-stack finance management platform designed to help users intelligently manage their personal finances.

Unlike traditional expense trackers, this application integrates Artificial Intelligence to automate expense categorization, analyze spending habits, predict future expenses, provide savings recommendations, and generate financial reports.

The application offers a premium SaaS-style user experience with a responsive interface and interactive analytics.

---

# ✨ Features

## 🔐 Authentication

- User Registration
- Secure Login
- JWT Authentication
- Google Sign-In
- Forgot Password
- Profile Management

---

## 💳 Expense Management

- Add Expenses
- Edit Expenses
- Delete Expenses
- Search Expenses
- Filter by Category
- Sort Transactions
- Upload Receipt Images
- Payment Methods
- Tags & Notes

---

## 💰 Income Management

- Salary
- Freelancing
- Business
- Investments
- Bonus
- Other Income Sources

---

## 📊 Dashboard

- Total Balance
- Total Income
- Total Expenses
- Monthly Spending
- Savings Overview
- Financial Health Score
- Budget Progress
- Interactive Charts
- Recent Transactions

---

# 🤖 AI Features

### AI Expense Categorization

Automatically categorizes expenses using AI.

Example

```
"I spent ₹450 at Domino's"
```

Automatically extracts:

- Amount
- Merchant
- Category
- Date

---

### AI Finance Chat

Ask questions like:

- How much did I spend this month?
- Show my biggest expenses.
- Compare this month with last month.
- Suggest savings.
- Predict next month's spending.

---

### Receipt OCR

Upload receipt images.

Automatically extracts:

- Merchant
- Amount
- Date
- Tax
- Items

Creates expense entries automatically.

---

### Voice Expense Entry

Users can say:

```
"I spent ₹300 on petrol"
```

The application converts speech into an expense.

---

### Smart Financial Insights

AI generates insights such as:

- Highest spending category
- Monthly comparison
- Spending trends
- Savings opportunities
- Budget analysis

---

### Expense Prediction

Predicts future expenses using historical spending.

---

### Savings Advisor

Provides personalized savings recommendations.

---

### Financial Health Score

Calculates a score based on:

- Spending habits
- Budget usage
- Savings rate
- Income vs Expenses

---

### Smart Notifications

- Budget alerts
- Bill reminders
- Subscription renewals
- Goal reminders
- Large transaction alerts

---

# 🧠 AI Agent Architecture

The application includes specialized AI agents.

- Expense Agent
- Budget Agent
- Analytics Agent
- Forecast Agent
- Savings Advisor Agent
- Receipt OCR Agent
- Voice Assistant Agent
- Report Generator Agent
- Notification Agent
- AI Chat Agent

---

# 🛠 Tech Stack

## Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- Framer Motion
- Recharts
- Axios

## Backend

- Node.js
- Express.js
- TypeScript

## Database

- MongoDB Atlas
- Mongoose

## Authentication

- JWT
- Google OAuth

## AI

- OpenAI API

## Storage

- Cloudinary

## Deployment

- Docker
- Docker Compose

---

# 📂 Project Structure

```
financepro/

├── frontend/
│   ├── src/
│   ├── public/
│   ├── Dockerfile
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── services/
│   ├── Dockerfile
│   └── package.json
│
├── docker-compose.yml
├── README.md
└── .env.example
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/financepro.git

cd financepro
```

---

## Install Frontend

```bash
cd frontend

npm install

npm run dev
```

---

## Install Backend

```bash
cd backend

npm install

npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

JWT_REFRESH_SECRET=your_refresh_secret

OPENAI_API_KEY=your_openai_key

GOOGLE_CLIENT_ID=your_google_client_id

GOOGLE_CLIENT_SECRET=your_google_client_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret

CLIENT_URL=http://localhost:5173
```

---

# 🐳 Docker Deployment

Build the project

```bash
docker compose build
```

Run the application

```bash
docker compose up
```

Run in background

```bash
docker compose up -d
```

Stop containers

```bash
docker compose down
```

---

# 📈 Future Enhancements

- Investment Portfolio Tracking
- AI Tax Assistant
- Family Expense Sharing
- Multi-Currency Support
- UPI Integration
- Email Reports
- Mobile Application
- AI Financial Coach
- Offline Mode
- Wearable Device Integration

---

# 🎯 Learning Outcomes

This project demonstrates:

- Full Stack Development
- MERN Stack
- REST API Development
- Authentication
- MongoDB Integration
- Docker Deployment
- Artificial Intelligence Integration
- OCR Processing
- Voice Recognition
- Responsive UI Design
- SaaS Dashboard Development
- Data Visualization

---

# 👨‍💻 Developer

**Muthukavi Dharshini M**

B.Tech – Computer Science and Business Systems

V.S.B Engineering College

---

# ⭐ If you found this project useful, consider giving it a star on GitHub!
