
# E-Commerce Web Application — Online Shoe Retail Platform

A comprehensive full-stack e-commerce web application designed for online shoe retail, offering a seamless, secure, and scalable shopping experience for users and administrators.

![E-Commerce Web Application](A_flat-design_digital_illustration_showcases_a_ban.png)

## Project Overview

This project focuses on building a robust and scalable online shopping platform specifically for shoe retail. Users can browse products, manage their shopping cart, track orders, and securely complete transactions. Admins can manage inventory, orders, and user accounts from a dedicated dashboard.

### Key Features

- **Product Browsing**: Users can explore a catalog of shoes with detailed descriptions and filtering options.
- **Shopping Cart Management**: Add, remove, and update cart items with real-time updates.
- **User Authentication**: Secure login and registration using JWT and OAuth mechanisms.
- **Order Tracking**: View real-time order status and updates.
- **Inventory Management**: Admin panel for managing product listings and stock levels.
- **Payment Integration**: Secure online payments using Stripe gateway.
- **Responsive Design**: Optimized for mobile and desktop experiences.

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT, OAuth
- **Payment Gateway**: Stripe API

## Getting Started

### Prerequisites

- Node.js 18+ 
- MongoDB Database
- Stripe API keys

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ecommerce-webapp.git
   cd ecommerce-webapp
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open http://localhost:5000 in your browser.

### Deploying to Production

To deploy the app, ensure environment variables are correctly set on your cloud platform (like Render, Heroku, or Vercel) and connect the database securely.

## Project Structure

```
├── client/               # Frontend files (HTML, CSS, JavaScript)
├── server/               # Backend files (Node.js, Express.js)
│   ├── controllers/      # Request handlers
│   ├── models/           # Mongoose models (Product, User, Order)
│   ├── routes/           # API routes
│   ├── middleware/       # Authentication and error handling
│   └── config/           # Database and API configuration
├── .env                  # Environment variables (not committed)
├── package.json          # Project metadata and dependencies
└── README.md              # Project documentation
```

## Academic Acknowledgements

This project was developed independently as part of a personal portfolio to demonstrate full-stack development skills and secure e-commerce application design.

## License

This project is for educational and demonstration purposes. Commercial use without permission is not allowed.

## Acknowledgements

- Stripe for secure payment processing
- MongoDB for NoSQL database services
- Open-source libraries and tools used during development
