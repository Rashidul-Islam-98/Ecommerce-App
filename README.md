# E-commerce App
  https://ecommerce-app-e7bu.vercel.app/

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [User Guide](#user-guide)
- [Seller Guide](#seller-guide)
- [Admin Section](#admin-section)
- [License](#license)

## Overview

This e-commerce app is a feature-rich platform that enables users to buy and sell products. It offers a seamless shopping experience with various features for users, sellers, and administrators. Users can browse products, add them to their cart, wishlist items, and securely make payments. Sellers can list their products, manage orders, and interact with buyers, while administrators have access to the entire system's data.

## Features

- User registration and authentication
- Product browsing and searching by category
- Shopping cart and wishlist functionality
- Secure checkout with multiple payment options (credit/debit card, PayPal, cash on delivery)
- User dashboard for profile management, password change, order tracking, and chatting with sellers
- Seller dashboard for product and event management, order tracking, and seller profile updates
- Admin section for overseeing users, orders, products, payments, and more
- Responsive design for a seamless experience on various devices

## Technologies Used

- Frontend:
  - React
  - Redux for state management
  - Tailwind CSS for styling
- Backend:
  - Express.js
  - MongoDB for the database
  - Socket.io for real-time chat functionality

## Installation

To run this e-commerce app locally, follow these steps:

1. Clone the repository:
   https://github.com/Rashidul-Islam-98/Ecommerce-App.git
2. Navigate to the project directory:
   cd Ecommerce-App
3. Install dependencies for the client ,server and socket-server:
   npm install
4. Configure environment variables for your project, including database credentials and API keys.

## Usage

To start the app, follow these steps:

1. Navigate to backend and start the server:
   cd backend
   npm run dev / npm start
2. Navigate to the socket and start socket:
   cd socket
   npm start
3. Navigate to the frontend and start server:
   cd frontend
   npm start
4. Vistit "http://localhost:3000"

Note: For cors issues, there need to make some changes in backend. Set frontend link in the cors origin and backend/controller/user and hop.

## User Guide

- Register and log in to access user-specific features.
- Browse products, search by category, and add items to the cart and wishlist.
- Use the user dashboard to manage your profile, change your password, track orders, and chat with sellers.
- Make secure payments using various methods, including credit/debit cards, PayPal, or cash on delivery.

## Seller Guide

- Register and log in as a seller to access seller-specific features.
- Use the seller dashboard to create and manage products and events, track orders, and update your seller profile.
- Interact with buyers and manage your product listings.

## Admin Section

- Access the admin section to oversee user accounts, orders, products, payments, and other system data.
- Perform administrative tasks as needed to maintain the platform.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


