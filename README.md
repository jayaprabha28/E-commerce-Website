#Project Overview:
----------------
This project is a food e-commerce application built with a MERN stack (MongoDB, Express.js, React.js, Node.js) that allows users to browse products, manage a shopping cart, and proceed to checkout.

#Features
----------------
*User authentication
*Product browsing by category
*Cart functionality (add, remove, update quantities)
*Order summary and checkout process
*Responsive design

#Technologies
--------------------
*Frontend: React.js, Redux, HTML, CSS
*Backend: Node.js, Express.js, MongoDB
*Database: MongoDB
*Icons: Font Awesome for icons

#Prerequisites
----------------------
*Node.js: Ensure you have Node.js installed. You can download it from nodejs.org.
*MongoDB: Make sure you have MongoDB installed and running locally, or use a cloud service like MongoDB Atlas.

#Installed Applications
---------------------------
*Node.js: Required for running the server and client applications.
*MongoDB: Required for database management.
*NPM (Node Package Manager): Comes with Node.js and is used to manage dependencies.

#Commands to Install Dependencies
-----------------------------
Backend Setup

cd backend

npm install express mongoose cors dotenv

Frontend Setup

cd frontend

npm install react-redux @reduxjs/toolkit react-router-dom axios

#Backend Setup
-------------------
Create a .env file in the backend directory with the following variables
PORT=5000
MONGO_URI=your_mongodb_uri

Start the backend server:
node server.js

#Frontend Setup
------------------------
npm start

#How to Run the Application
--------------------------
1.Start MongoDB: Ensure your MongoDB server is running.
2.Start the backend server
cd backend
node server.js

3.Start the frontend application:

cd frontend
npm start

4.Open your browser and navigate to http://localhost:3000 to view the application.
