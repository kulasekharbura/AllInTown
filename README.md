
AllInTown: A MERN Stack E-commerce Platform for Local Shopping
This project is a full-stack e-commerce and delivery platform built to connect consumers directly with local shops. Unlike large-scale delivery services, AllInTown allows users to browse and order specifically from their favorite and trusted local stores.

The platform provides a comprehensive solution for local communities, empowering shop owners with a digital presence and giving consumers a convenient way to support local businesses.

Key Features
Multi-Role System: The application supports three distinct user roles:

Consumers can explore local shops, manage their shopping cart, save addresses, place orders, and track their delivery history.

Sellers have a dedicated dashboard to manage their shops, add/edit items, handle incoming orders, and assign them to a delivery person.

Delivery Boys are provided with an interface to view their assigned deliveries and update the order status.

Seamless Cart Management: The shopping cart works for both guest users and authenticated users. A guest's cart is automatically merged with their account upon logging in.

Full Order Workflow: The platform manages the entire order lifecycle, from initial placement to final delivery, with a clear status system.

Technology Stack
Frontend: React.js, React Router, Material-UI (MUI)

Backend: Node.js, Express.js

Database: MongoDB (Mongoose)

Authentication: Passport.js with a local strategy, bcrypt for secure password hashing.

Getting Started
Follow these steps to set up and run the project locally.

Prerequisites

Node.js (>=18)

MongoDB

Clone the repository:

Bash

git clone https://github.com/kulasekharbura/allintown.git
cd allintown
Set up the Backend:

Navigate to the backend directory.

Install dependencies: npm install

Create a .env file with your MongoDB URI and a session secret.

MONGO_URI="mongodb://localhost:27017/allintown"
SESSION_SECRET="your_secret_key"
PORT=8080
Start the server: npm run test

Set up the Frontend:

Navigate to the frontend directory.

Install dependencies: npm install

Create a .env file to point to your backend.

VITE_API_URL="http://localhost:8080"
Start the development server: npm run dev

The application will be available at http://localhost:5173.

Live Demo
Explore the live version of the project here: http://all-in-town.vercel.app
