-> User Feedback System
A modern, responsive feedback collection application built using Express.js, MongoDB, and Bootstrap 5.
It allows users to submit feedback through a user-friendly form and sends email alerts to administrators for every new submission.
Admins can view and manage all feedback from a dedicated dashboard.

-> Key Features
Interactive feedback form with a clean and simple UI
Email notifications to the admin on each new feedback submission
Admin dashboard with detailed feedback listings and statistics
Responsive design using Bootstrap 5 for all devices
MongoDB database integration for secure data storage

-> Prerequisites
Node.js and npm
MongoDB (local or MongoDB Atlas)
Gmail account for email notifications

-> Setup Instructions
1. Clone the Repository
   git clone https://github.com/priti-kumari56/User_feedback_system.git
   cd User_feedback_system

2. Install Project Dependencies
   npm install

3. Configure Environment Variables
Create a .env file in the root of the project and add the following:
PORT=3000
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-app-specific-password
ADMIN_EMAIL=admin@example.com
MONGODB_URI=mongodb://localhost:27017/feedback-app
Note: If you're using Gmail, enable 2-Step Verification and generate an App Password to use as EMAIL_PASS.

4. Start MongoDB
If using local MongoDB, ensure the service is running using mongod
If using MongoDB Atlas, replace the MONGODB_URI with your connection string

5. Launch the Application
   node app.js

-> Application Usage
Open your browser and visit: http://localhost:3000 → Submit feedback
Visit http://localhost:3000/admin → Admin dashboard to view feedback, ratings, and messages

-> Email Setup (Using Gmail)
Enable 2-Step Verification on your Gmail account
Go to Google Account > Security > App Passwords
Generate a new App Password
Use this password as EMAIL_PASS in your .env file

-> Technologies Used
Backend: Node.js, Express.js
Database: MongoDB with Mongoose
Frontend: HTML, Bootstrap 5, EJS templates
Email Service: Nodemailer with Gmail SMTP




