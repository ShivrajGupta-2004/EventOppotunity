EventOpportunity – Full-Stack Event Management System

EventOpportunity is a full-stack web application used to manage and display events. It includes user registration, login authentication, event creation features, and automated email notifications using Nodemailer.

Download Links

Project ZIP (36 MB):
https://drive.google.com/file/d/1jJv1RmWdBfTT911LwoEKQfCR-EfyTqB3/view

Documentation (Black Book PDF):
https://drive.google.com/file/d/1Gm0tCN8sl5Yamt0Vgulx6oije4JFHZfv/view

Technologies Used

Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Email Service: Nodemailer
Authentication: JSON Web Tokens (JWT)

Project Structure

Below is the folder structure in a GitHub-friendly format:
EventOpportunity/
│
├── server.js
├── package.json
├── .env.example
│
├── routes/
│   └── (API route files)
│
├── models/
│   └── (MongoDB schema files)
│
├── controllers/
│   └── (Business logic)
│
├── config/
│   └── (Configuration files)
│
└── public/
    ├── index.html
    ├── userRegister.html
    ├── css/
    ├── js/
    └── images/
Key Features

Secure user registration and login

JWT-based authentication

Create, update, delete events

Automatic email notifications

MongoDB database storage

Responsive frontend

RESTful API

Easy setup and deployment

Installation and Setup Guide
1. Install Required Software

Install the following before starting:

Node.js (version 14 or above)

MongoDB

Gmail account for sending emails

2. Download and Extract the Project

Download the ZIP from the link above

Extract it to your system

3. Install Dependencies

Open the terminal inside the project folder:

cd EventOpportunity
npm install

4. Create Environment Variables

Create a new file named .env in the project root and add:

PORT=3000
MONGODB_URI=mongodb://localhost:27017/eventopportunity
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-gmail-app-password
JWT_SECRET=your-secret-key-here

5. Generate Gmail App Password

Open Google Account

Go to "Security"

Enable "2-Step Verification"

Open "App Passwords"

Select "Mail" and generate a password

Copy the 16-digit password into .env as EMAIL_PASS

6. Start MongoDB

Open a new terminal and run:

mongod


Keep this terminal open.

7. Start the Application

Run:

npm start

8. Access the Website

Open your browser:

http://localhost:3000
Troubleshooting

Email Problems:

Confirm Gmail App Password

Ensure 2-Step Verification is enabled

Use App Password (not normal password)

MongoDB Problems:

Check if MongoDB is running

Confirm the MONGODB_URI in .env

Port Already in Use:

Change PORT to 3001 or 3002 in .env

npm install Errors:

Delete node_modules and package-lock.json

Run npm install again

Documentation

The Black Book PDF contains:

Complete setup

Code explanation

API documentation

Database schema

Deployment guide

Troubleshooting tips

Project Information

Project Name: EventOpportunity
Version: 1.0.0
Total Size: 36 MB
License: MIT

Support

Refer to the PDF documentation for detailed guidance.
Check console logs for errors.
Review API endpoints and backend code for debugging.

This is the cleanest and most professional GitHub-ready version with no emojis, no extra styling, and proper formatting.

If you want, I can also create:

A shorter README

A version with screenshots

A version with GitHub badges
