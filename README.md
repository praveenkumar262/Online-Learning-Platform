# Online Learning Platform (OLP)

An online learning platform built using the MERN stack (MongoDB, Express.js, React, Node.js). The platform allows users to browse and enroll in courses, track their progress, and earn certificates upon completing courses. Teachers and admins can manage the courses and users.

# Table of Contents
About the Project
Features
Installation
Usage
Project Structure
Technology Stack
Contributing
License
Contact
# About the Project
Online Learning Platform (OLP) is a full-stack web application designed to enhance the learning experience by providing an interactive online space where users can access a wide variety of courses, track their progress, and get certifications upon completion. The project is developed using the MERN stack:

MongoDB: NoSQL database for storing user data and course information.
Express.js: Web framework for building the backend API.
React: Frontend library for building the user interface.
Node.js: Backend runtime for executing JavaScript server-side.
# Features
User Authentication: Users can sign up, log in, and manage their accounts.
Course Management: Teachers can create, update, and delete courses.
Course Enrollment: Students can enroll in courses and track their progress.
Progress Tracking: Users can track their learning progress with completion percentages.
Certification: Users receive a certificate when they complete a course.
Role-based Access: Differentiated roles for users, teachers, and admins.
# Installation
To set up the project on your local machine, follow these steps:

## Prerequisites
Node.js (Download from here)
MongoDB (Set up a MongoDB Atlas account or install MongoDB locally)
# Steps to Install
## Clone the repository:

git clone https://github.com/yourusername/Online-Learning-Platform.git
cd Online-Learning-Platform
## Install dependencies:

Navigate to the frontend and backend folders to install necessary dependencies.

For frontend:

cd frontend
npm install
For backend:

cd ../backend
npm install
## Start the development server:

In the frontend directory, start the React development server:

cd frontend
npm run dev
In the backend directory, start the backend server:

cd backend
npm start
# Usage
Once the app is running:

Open the frontend in your browser at http://localhost:5172.
Sign Up as a new user or Login if you already have an account.
Explore the available courses, enroll, and track your progress.
Teachers can create and manage courses, while admins have full control over users and courses.
# Project Structure
Online-Learning-Platform/
├── frontend/
│   ├── public/          # Public assets (e.g., images, fonts)
│   ├── src/             # React components and other source files
│   ├── package.json     # Frontend dependencies and scripts
├── backend/
│   ├── config/          # Configuration files (e.g., database setup)
│   ├── models/          # MongoDB models (User, Course, etc.)
│   ├── routes/          # Express.js route handlers
│   ├── server.js        # Main backend server file
│   ├── package.json     # Backend dependencies and scripts
└── README.md            # This file
# Technology Stack
The following technologies are used in this project:

## Frontend:
React.js
Bootstrap, Material UI (for styling)
## Backend:
Node.js
Express.js
## Database:
MongoDB (MongoDB Atlas for cloud hosting)
## Authentication:
JWT (JSON Web Token)
bcrypt.js (for hashing passwords)
## Other Libraries:
Axios (for API requests)
Cors (for handling cross-origin requests)

