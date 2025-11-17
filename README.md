EventOpportunity - Complete Project Package
Project Description
EventOpportunity is a full-stack web application for managing and displaying events and opportunities with user registration and automated email notifications.
Download Links
Project Files (ZIP - 36 MB)
https://drive.google.com/file/d/1jJv1RmWdBfTT911LwoEKQfCR-EfyTqB3/view?usp=sharing
Documentation (Black Book PDF)
https://drive.google.com/file/d/1Gm0tCN8sl5Yamt0Vgulx6oije4JFHZfv/view?usp=drive_link

Technologies Used

Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Email Service: Nodemailer
Authentication: JWT (JSON Web Tokens)

What's in the ZIP File?
EventOpportunity/ (36 MB)
├── server.js                 # Main server file
├── routes/                   # API routes
├── models/                   # Database models
├── controllers/              # Business logic
├── config/                   # Configuration files
├── public/                   # Frontend files
│   ├── index.html           # Home page
│   ├── userRegister.html    # Registration page
│   ├── css/                 # Stylesheets
│   ├── js/                  # JavaScript files
│   └── images/              # Image assets
├── package.json             # Project dependencies
├── .env.example             # Environment variables template
└── README.md                # Documentation
Key Features

User Registration & Authentication - Secure signup and login system
Event Management - Create, edit, and delete events easily
Email Notifications - Automatic email alerts via Nodemailer
MongoDB Database - Reliable data storage
RESTful API - Clean and organized API endpoints
Responsive Design - Works on all devices
JWT Security - Token-based authentication
Easy Deployment - Simple setup process


Installation & Setup Guide
Step 1: Prerequisites
Before starting, make sure you have:

Node.js (version 14 or higher) - Download from https://nodejs.org/
MongoDB - Download from https://www.mongodb.com/try/download/community
Gmail Account - For sending emails

Step 2: Download & Extract

Copy the Project ZIP link from above
Download the file (36 MB)
Extract to your preferred location

Step 3: Install Dependencies
Open terminal/command prompt in the project folder:
bashcd EventOpportunity
npm install
```

### Step 4: Configure Environment Variables

Create a new file named .env in the root folder and add:
```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/eventopportunity
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-gmail-app-password
JWT_SECRET=your-secret-key-here
Step 5: Setup Gmail App Password

Go to your Google Account settings
Click Security → 2-Step Verification (enable if not enabled)
Scroll down to App passwords
Select Mail and Generate
Copy the 16-character password
Paste it in .env file as EMAIL_PASS

Step 6: Start MongoDB
Open a new terminal and run:
bashmongod
Keep this terminal running.
Step 7: Run the Application
In your project terminal, run:
bashnpm start
```

### Step 8: Access the Website

Open your browser and go to:
```
http://localhost:3000

API Endpoints
MethodEndpointDescriptionPOST/api/registerRegister new userPOST/api/loginUser loginGET/api/eventsGet all eventsPOST/api/eventsCreate new eventPUT/api/events/:idUpdate eventDELETE/api/events/:idDelete event

Troubleshooting
Email Not Sending?

Check Gmail App Password is correct
Verify .env file configuration
Make sure 2-Step Verification is enabled
Use App Password, not regular Gmail password

MongoDB Connection Error?

Ensure MongoDB is running (mongod command)
Check MONGODB_URI in .env file
Verify MongoDB is installed correctly

Port Already in Use?

Change PORT number in .env file (e.g., 3001, 3002)
Or stop other applications using port 3000

Dependencies Not Installing?

Delete node_modules folder and package-lock.json
Run npm install again
Check your internet connection


Documentation
For detailed information, step-by-step tutorials, and advanced configurations, please refer to the Black Book PDF linked above. It contains:

Complete setup instructions
Code explanations
API documentation
Database schema details
Deployment guides
Common issues and solutions


Quick Start Tips

Read the Black Book first - It will save you time
Test email functionality - Use a test Gmail account initially
Keep MongoDB running - Don't close the MongoDB terminal
Check console logs - They help identify issues quickly
Backup your .env file - Keep your credentials safe


Package Information

Project Name: EventOpportunity
Version: 1.0.0
Total Size: 36 MB (includes all dependencies and assets)
License: MIT


Support & Help

Check the Black Book PDF for detailed documentation
Found a bug? Document it and refer to troubleshooting section
Need help? Review the API endpoints and code comments


Ready to Go!
Your EventOpportunity website is now ready to use. Follow the installation steps above, and you'll have a fully functional event management system running in minutes!
Happy Coding!
