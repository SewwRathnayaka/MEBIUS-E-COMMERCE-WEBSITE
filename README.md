# Full Stack E-Commerce Platform

Frontend: https://github.com/SewwRathnayaka/FED-FRONTEND.git


Backend: https://github.com/SewwRathnayaka/FED-BACKEND.git

## Overview
A modern e-commerce platform built with MERN stack (MongoDB, Express.js, React, Node.js) featuring user authentication, product management, shopping cart, and order processing.

## Project Structure
This repository contains both frontend and backend code:
- `/frontend` - React.js client application
- `/backend` - Node.js/Express.js REST API

## Tech Stack

### Backend
- Node.js & Express.js
- TypeScript
- MongoDB with Mongoose
- Clerk Authentication
- Zod Validation

### Frontend
- React.js
- Redux Toolkit
- Tailwind CSS
- React Router DOM
- Clerk Authentication
- React Hook Form

## Getting Started

### Backend Setup
1. Navigate to backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables in `.env`:
```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
CLERK_SECRET_KEY=your_clerk_secret
```

4. Start the server:
```bash
npm run dev
```

### Frontend Setup
1. Navigate to frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables in `.env`:
```
REACT_APP_CLERK_PUBLISHABLE_KEY=your_clerk_key
REACT_APP_API_URL=http://localhost:5000
```

4. Start development server:
```bash
npm start
```

## Features
- Product Browsing & Filtering
- Shopping Cart Management
- User Authentication
- Order Processing
- Admin Dashboard
- Responsive Design

## API Endpoints

### Products
- `GET /api/products` - Get all products
- `POST /api/products` - Create product (Admin)
- `PUT /api/products/:id` - Update product (Admin)
- `DELETE /api/products/:id` - Delete product (Admin)

### Categories
- `GET /api/categories` - Get all categories
- `POST /api/categories` - Create category (Admin)
- `PUT /api/categories/:id` - Update category (Admin)

### Orders
- `POST /api/orders` - Create order
- `GET /api/orders` - Get user orders
- `GET /api/orders/:id` - Get order details

## Project Structure

### Frontend
```
src/
├── components/     # Reusable UI components
├── pages/         # Route components
├── features/      # Redux slices
├── services/      # API services
└── utils/         # Helper functions
```

## Contributing
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License
MIT License