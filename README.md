# MyPHR

Public Health Record Management System
Overview
This project is a comprehensive web application designed to manage public health records efficiently. It allows patients, doctors, and administrators to interact with health records, prescriptions, and personal information securely. The application utilizes JWT for authentication and is built with Node.js, Express, and MongoDB for the backend, while the frontend is developed using React and Tailwind CSS.

Features
User Authentication: Secure login and registration for patients, doctors, and administrators.
Patient Management: Patients can register, log in, and view their health records and prescriptions.
Doctor Management: Doctors can log in, add prescriptions, and view patient details.
Admin Management: Admins can manage doctors and patients, including adding and deleting records.
Prescription Management: Doctors can create and manage prescriptions for patients.
Responsive Design: The application is designed to be mobile-friendly using Tailwind CSS.
File Structure
/client: Contains the React frontend application.
/src: Source files for the React application.
/public: Public assets and HTML files.
tailwind.config.js: Configuration file for Tailwind CSS.
/public_health_record_management_system: Contains the Node.js backend application.
/controllers: Business logic for handling requests and responses.
/models: Mongoose models for MongoDB collections (Patient, Doctor, Admin, Prescription).
/middlewares: Middleware functions for authentication and authorization.
/routes: Express routes for handling API endpoints.
/utils: Utility functions, such as token creation.
/README.md: Documentation for setting up and running the project.
Installation
Clone the repository:
bash
Insert Code
Run
Copy code
Navigate to the project directory:
bash
Insert Code
Run
Copy code
cd public_health_record_management_system
Install server dependencies:
bash
Insert Code
Run
Copy code
npm install
Navigate to the client folder and install dependencies:
bash
Insert Code
Run
Copy code
cd client
npm install
Start the client application:
bash
Insert Code
Run
Copy code
npm start
Return to the server directory and start the server:
bash
Insert Code
Run
Copy code
cd ..
node app.js
Environment Variables
To run this project, you will need to add the following environment variables to your .env file:

DATABASE: MongoDB connection URI.
SECRET_KEY: Secret key for signing and verifying JWT.
