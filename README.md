# Clothify - MERN E-commerce Web Application

## Overview

**Clothify** is a full-stack e-commerce web application built using the MERN (MongoDB, Express, React, Node.js) stack. It allows users to browse, search, and purchase clothing items, and provides an admin interface for managing products and orders.

## Features

- **User Authentication**: Secure login and registration system.
- **Product Management**: Admins can add, edit, and delete products.
- **Shopping Cart**: Users can add items to their cart and proceed to checkout.
- **Order Management**: Users can view their order history, and admins can manage orders.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Project Structure

- **backend/**: Contains server-side code using Node.js and Express.
- **data.json**: Sample data for populating the database.
- **index.html**: Entry point for the React frontend.
- **package.json**: Lists project dependencies and scripts.
- **script.js**: Frontend JavaScript code.
- **server.js**: Main server-side file for handling requests.
- **style.css**: Stylesheet for the frontend.

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd clothify
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up the backend**:
   - Navigate to the `backend/` directory.
   - Install backend dependencies:
     ```bash
     npm install
     ```
   - Configure environment variables (e.g., MongoDB connection URI).

4. **Run the application**:
   - Start the backend server:
     ```bash
     node server.js
     ```
   - Start the frontend:
     ```bash
     npm start
     ```

## Usage

- Open your browser and go to `http://localhost:3000` to view the application.
- Use the admin credentials to log in and manage products and orders.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
