# Product List Application

A simple web application that displays a list of products in card format with delete functionality.

## Tech Stack

### Frontend
- React
- Material UI
- Axios

### Backend
- Node.js
- Express.js

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
bash
cd StarterCode/backend

2. Install dependencies:
bash
npm install

3. Start the backend server:
bash
node index.js

The backend server will run on http://localhost:5000

### Frontend Setup

1. Open a new terminal and navigate to the frontend directory:
bash
cd StarterCode/frontend

2. Install dependencies:
bash
npm install


3. Install additional Material UI dependencies:
bash
npm install @mui/material @mui/icons-material @emotion/react @emotion/styled axios

4. Start the frontend development server:
bash
npm start


The frontend application will open automatically in your default browser at http://localhost:3000

## Features

- Responsive product card layout
- Product information display (name, description, price, image)
- Delete functionality for products
- Automatic layout adjustment after deletion
- Data persistence with backend integration

## API Endpoints

### GET /api/products
- Fetches all products
- Returns an array of product objects

### DELETE /api/products/:id
- Deletes a specific product by ID
- Returns success/failure message

