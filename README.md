Smart Energy Management and Alert System

Overview

The Smart Energy Management and Alert System is designed to help users optimize their energy consumption by providing real-time alerts and live energy tariff prices. This innovative system empowers users to make informed decisions about their energy usage, leading to cost savings and sustainable living.

Key Features

Live Tariff Pricing: Displays real-time energy prices on the website, helping users plan their energy consumption effectively.

Energy Usage Alerts: Sends personalized email notifications suggesting the optimal times to use high, medium, or low power-consuming appliances.

User Authentication: Allows users to register, log in, and manage their accounts securely.

Appliance Recommendations: Provides tailored suggestions for appliance usage based on live energy tariffs.

How It Works

Users register and log in to the system via a secure authentication process.

Real-time tariff data is fetched and displayed on the website.

The system analyzes tariff data and sends email alerts recommending optimal energy usage periods.

Users receive actionable suggestions to reduce costs and energy consumption.

Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: Node.js, Express.js

Email Notifications: Nodemailer

User Authentication: bcrypt (for password hashing)

Scheduling: node-schedule (for periodic alerts)

Environment Variables: dotenv (for secure configuration management)

Database: [Specify if used, e.g., MongoDB]

Installation Guide

Prerequisites

Node.js (v14 or higher)

npm (Node Package Manager)

Steps to Run the Project Locally

Clone the Repository

git clone https://github.com/your-username/your-repository-name.git

Install Dependencies

cd your-repository-name
npm install

Set Up Environment Variables
Create a .env file in the root directory and add the following:

GMAIL_USER=your-email@gmail.com
GMAIL_PASS=your-email-app-password

Run the Server

node server.js

The server will run on http://localhost:5005.

Access the Website
Open index.html in your browser to access the frontend. If a framework like React or Vue.js is used, serve the frontend using npm start or a similar command.
