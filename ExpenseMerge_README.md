# 💰 ExpenseMerge

**A Scalable Full-Stack Financial Platform for Expense Splitting &
Personal Finance Management**

ExpenseMerge is a modern MERN-stack application that combines
peer-to-peer expense splitting with personal finance tracking in one
unified platform. It eliminates the need for multiple fragmented tools
by providing secure, scalable, and reliable financial collaboration
features.

Built with a modular architecture, ExpenseMerge supports independent
frontend/backend deployments, advanced security, flexible payment
models, and enterprise-grade performance optimization.

------------------------------------------------------------------------

## 🚀 Key Features

### 👥 Group Expense Management

-   Create groups and manage shared expenses\
-   Invite members via email (even before they register)\
-   Automatically link historical expenses upon signup

### 🔐 Secure Authentication & Authorization

-   JWT-based authentication using HTTP-only cookies\
-   Google Sign-In via OAuth 2.0 / OpenID Connect\
-   Password hashing with bcrypt\
-   Protected routes with middleware validation

### 🧑‍💼 Role-Based Access Control (RBAC)

-   Multi-account financial access\
-   Controlled permissions for family members, friends, or financial
    advisors\
-   Fine-grained data visibility and access control

### 💳 Payment & Subscription System

-   Credit-based purchases and subscription billing\
-   Reliable transaction handling with webhook verification\
-   Automatic recovery from network failures

### ⚡ High Performance & Scalability

-   Server-side pagination and sorting\
-   Optimized database queries for large datasets\
-   Decoupled architecture for independent scaling\
-   API-ready backend for mobile expansion

### 🧩 Modular System Architecture

-   Separate frontend and backend codebases\
-   RESTful API communication\
-   Microservices-ready structure

------------------------------------------------------------------------

## 🏗️ Tech Stack

**Frontend** - React.js - Context API / State Management - REST API
Integration

**Backend** - Node.js - Express.js - MongoDB - JWT Authentication -
Middleware-based authorization

**Security** - OAuth 2.0 / OIDC - HTTP-only cookies - bcrypt password
hashing - Environment-based secret management

**Payments** - Razorpay integration - Webhook-based transaction
validation

------------------------------------------------------------------------

## 📂 Project Structure

ExpenseMerge/ │ ├── frontend/ \# React client application │ ├──
components/ │ ├── pages/ │ ├── services/ │ └── ... │ ├── backend/ \#
Express REST API │ ├── controllers/ │ ├── models/ │ ├── routes/ │ ├──
middleware/ │ └── ... │ └── README.md

------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

git clone `<repo-url>`{=html}\
cd ExpenseMerge

------------------------------------------------------------------------

### 2️⃣ Backend Setup

cd backend\
npm install

Create .env file:

PORT=\
MONGO_URI=\
JWT_SECRET=\
GOOGLE_CLIENT_ID=\
GOOGLE_CLIENT_SECRET=\
RAZORPAY_KEY_ID=\
RAZORPAY_SECRET=

Run server:\
npm start

------------------------------------------------------------------------

### 3️⃣ Frontend Setup

cd frontend\
npm install\
npm start

------------------------------------------------------------------------

## 🔑 Environment & Security Practices

-   Sensitive keys stored in environment variables\
-   No secrets exposed to client\
-   Only public configuration shared with frontend\
-   Secure cookie-based session management

------------------------------------------------------------------------

## 🔌 API Design Principles

-   RESTful routing conventions\
-   Centralized error handling\
-   Middleware-based authentication\
-   Input validation layer\
-   Modular controllers

------------------------------------------------------------------------

## 📈 Performance Optimizations

-   Server-side pagination\
-   Indexed database queries\
-   Minimal payload responses\
-   Optimized request lifecycle

------------------------------------------------------------------------

## 🌐 Deployment Strategy

-   Independent frontend/backend deployment\
-   Scalable cloud-ready backend\
-   API-driven architecture for mobile apps

------------------------------------------------------------------------

## 🎯 Use Cases

-   Friends splitting expenses\
-   Families managing shared finances\
-   Financial advisors monitoring accounts\
-   Subscription-based financial services

------------------------------------------------------------------------

## 🛣️ Future Roadmap

-   Mobile application (React Native)\
-   AI-based spending insights\
-   Budget forecasting\
-   Multi-currency support\
-   Real-time notifications\
-   Microservice containerization

------------------------------------------------------------------------

## 🤝 Contributing

Contributions are welcome.

1.  Fork repository\
2.  Create feature branch\
3.  Commit changes\
4.  Open pull request

------------------------------------------------------------------------

## 📜 License

This project is licensed under the MIT License.

------------------------------------------------------------------------

## 👨‍💻 Author

Developed as a scalable full-stack financial platform using the MERN
ecosystem.
