EventOpportunity – Full-Stack Event Management System

EventOpportunity is a full-stack web application designed to manage and display events with secure user registration, JWT-based authentication, and automated email notifications powered by Nodemailer.

📥 Download Resources

Project ZIP (36 MB)
https://drive.google.com/file/d/1jJv1RmWdBfTT911LwoEKQfCR-EfyTqB3/view

Documentation – Black Book PDF
https://drive.google.com/file/d/1Gm0tCN8sl5Yamt0Vgulx6oije4JFHZfv/view

🚀 Tech Stack

Frontend:

HTML

CSS

JavaScript

Backend:

Node.js

Express.js

Database:

MongoDB

Email Service:

Nodemailer

Authentication:

JSON Web Tokens (JWT)

📂 Project Structure
EventOpportunity/
├── server.js               # Main server entry
├── routes/                 # API routes
├── models/                 # MongoDB models
├── controllers/            # Business logic
├── config/                 # App configuration
├── public/                 # Frontend files
│   ├── index.html
│   ├── userRegister.html
│   ├── css/
│   ├── js/
│   └── images/
├── package.json            # Dependencies list
├── .env.example            # Environment variable template
└── README.md               # Project documentation

⭐ Core Features

🔐 Secure User Registration & Login (JWT-based)

📅 Event Management (Create, update, delete)

📧 Automatic Email Notifications via Nodemailer

🗄 MongoDB Database Storage

📱 Responsive UI for all devices

🔗 RESTful API Architecture

🚀 Easy Setup & Deployment

🛠 Installation & Setup
1. Install Prerequisites

Ensure the following are installed:

Node.js (v14+)

MongoDB

Gmail account (for emails)

2. Download Project

Download the ZIP from the link above

Extract to any folder

3. Install Dependencies
cd EventOpportunity
npm install

4. Configure Environment Variables

Create a .env file in the root directory:

PORT=3000
MONGODB_URI=mongodb://localhost:27017/eventopportunity
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-gmail-app-password
JWT_SECRET=your-secret-key-here

5. Generate Gmail App Password

Google Account → Security

Enable 2-Step Verification

Go to App Passwords

Select Mail → Generate

Copy the generated 16-character password

Paste it into .env as EMAIL_PASS

6. Start MongoDB
mongod


Keep this terminal open.

7. Start the Application
npm start

8. Open in Browser
http://localhost:3000

📡 API Endpoints
Method	Endpoint	Description
POST	/api/register	Register new user
POST	/api/login	User login
GET	/api/events	Get all events
POST	/api/events	Create new event
PUT	/api/events/:id	Update existing event
DELETE	/api/events/:id	Delete event
🔧 Troubleshooting Guide
Email Not Sending?

Check Gmail App Password

Ensure 2-Step Verification is ON

Use App Password, not normal Gmail password

MongoDB Not Connecting?

Confirm mongod is running

Verify MONGODB_URI

Check MongoDB installation

Port Already in Use?

Change PORT in .env (e.g., 3001)

Close other running Node processes

npm Install Errors?

Delete node_modules & package-lock.json

Run npm install again

📘 Documentation

The complete Black Book PDF includes:

Detailed setup guide

Explanation of backend code

API documentation

Database schema

Deployment instructions

Error handling & fixes

📦 Project Details

Name: EventOpportunity

Version: 1.0.0

Size: 36 MB

License: MIT

🤝 Support

For help or debugging:

Refer to console logs

Review API endpoints

Read the Black Book documentation

🎉 You're Ready to Go!

Your EventOpportunity website is fully set up and ready to run.
Enjoy building and expanding your event management system!
