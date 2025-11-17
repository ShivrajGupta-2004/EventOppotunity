Event Opportunity Website
Description
Event Opportunity website for managing and displaying events and opportunities with user registration and email notifications.
Technologies Used

Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Email Service: Nodemailer
Authentication: JWT (if applicable)

Prerequisites

Node.js installed (v14 or higher)
MongoDB installed and running
Gmail account for sending emails

Installation & Setup

Upload EventOpportunity folder to your server
Install Dependencies

bash   cd EventOpportunity
   npm install
```

3. **Configure Environment Variables**
   Create a `.env` file in root directory:
```
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/eventopportunity
   
   EMAIL_USER=your-email@gmail.com
   EMAIL_PASS=your-app-password
   
   JWT_SECRET=your-secret-key

Get Gmail App Password

Go to Google Account settings
Security → 2-Step Verification → App passwords
Generate password for "Mail"
Use this password in .env file


Start MongoDB

bash   mongod

Run the Application

bash   npm start
```

7. **Access the Website**
   - Open browser: `http://localhost:3000`

## Folder Structure
```
EventOpportunity/
├── server.js
├── routes/
├── models/
├── controllers/
├── config/
├── public/
│   ├── index.html
│   ├── userRegister.html
│   ├── css/
│   ├── js/
│   └── images/
├── package.json
└── .env
Features

User registration & authentication
Event creation and management
Email notifications via Nodemailer
MongoDB database integration
RESTful API endpoints

API Endpoints

POST /api/register - User registration
POST /api/login - User login
GET /api/events - Get all events
POST /api/events - Create new event

Troubleshooting
Email not sending?

Check Gmail App Password
Enable "Less secure app access" (not recommended) OR use App Password
Verify .env configuration

MongoDB connection error?

Ensure MongoDB is running
Check connection string in .env

Port already in use?

Change PORT in .env file
