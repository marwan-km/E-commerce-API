
# E-Commerce API

## Hosted Project
- [E-Commerce API URL](https://node-course-e-commerce.onrender.com/)

## Description
This is a RESTful API for an E-commerce application. It supports features like user authentication, product management, order management, reviews, and more.

## Features
- User Authentication (Register, Login, Logout)
- CRUD operations for Products
- CRUD operations for Reviews
- Order Management
- JWT-based Authentication
- Secure Routes with Role-Based Access

## Technologies Used
- Node.js
- Express
- MongoDB
- JWT
- bcrypt
- dotenv

## Installation

### Prerequisites
- Node.js
- MongoDB
- GitHub account

### Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/marwan-km/E-commerce-API.git
   cd E-commerce-API
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables in `.env`:
   - `MONGO_URL`: Your MongoDB connection string.
   - `JWT_SECRET`: Secret for JWT.
   - `JWT_LIFETIME`: JWT token expiration time.

4. Start the server locally:
   ```bash
   npm start
   ```

## Deployment

#### **Deploy your app**

- **Note:** You can deploy your app using various platforms such as Render, Vercel, or AWS. Follow the platform's instructions for deploying a Node.js app with MongoDB.
