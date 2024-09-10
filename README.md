﻿# ShrareRooms
Sharerooms - Hotel Management System (MERN Stack)
Sharerooms is an advanced hotel management system developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). It offers users the ability to search, browse, and select hotel rooms based on their specific requirements. This project focuses on delivering an intuitive, responsive, and scalable solution for hotel booking management.

Currently, the project is in development, with new features continuously being added to enhance the user experience.

Table of Contents
About the Project
Features
Tech Stack
Installation
Usage
API Endpoints
Folder Structure
Project Status
Contributing
License
Contact
About the Project
Sharerooms provides a flexible platform for users to:

Search for hotels in various locations.
Select rooms based on criteria such as price, size, and amenities.
View detailed room descriptions and images.
(Future feature) Book rooms and complete payments online.
Manage and track room bookings through a user dashboard.
The project leverages MongoDB for data storage, Express.js and Node.js for server-side logic, and React.js for the client-side user interface, ensuring a seamless and high-performing experience for both users and administrators.

Features
Comprehensive Hotel Search:

Users can browse hotels based on location, price, and amenities.
Filter rooms by availability, price range, room size, and additional services.
Room Details:

View images, descriptions, and real-time availability of rooms.
Comprehensive information on amenities (Wi-Fi, breakfast, air conditioning, etc.).
Dynamic User Interface:

Responsive design optimized for mobile, tablet, and desktop platforms.
Dynamic updates using React.js for fast page transitions and interactions.
Room Booking System (Upcoming):

Users can select and book available rooms directly through the platform.
Integrated payment gateway for seamless transactions (coming soon).
User Profiles:

(Future feature) Allow users to create profiles, manage their bookings, and track reservation history.
Secure authentication using JWT (JSON Web Tokens).
Admin Dashboard (Upcoming):

Admins can manage hotels, rooms, bookings, and user profiles.
View analytics for hotel performance, user activity, and booking trends.
Tech Stack
The application is built using the MERN stack to ensure scalability and efficiency.

Frontend: React.js with Hooks and React Router for seamless navigation.
Backend: Node.js with Express.js for handling API requests and server-side logic.
Database: MongoDB for storing hotel, room, user, and booking information.
Authentication: (Planned) JWT for user authentication and secure access.
State Management: React Context API for global state management.
Styling: CSS and future plans for integrating Material-UI or Bootstrap for UI components.
Installation
Follow these steps to set up and run the project locally:

Clone the repository:

git clone https://github.com/yourusername/sharerooms.git
Navigate to the project directory:

cd sharerooms
Set up the backend:

Navigate to the backend folder:

cd backend
Install backend dependencies:

npm install
Create a .env file in the backend directory with the following variables:

MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret_key
Start the backend server:

npm start
Set up the frontend:

Navigate to the frontend folder:

cd ../frontend
Install frontend dependencies:

npm install
Start the frontend server:

npm start
Open your browser and navigate to http://localhost:3000 to access the app.

Usage
After setting up the project, launch the application by visiting http://localhost:3000.
Explore different hotels and filter rooms based on your preferences.
(Coming soon) Select a room and proceed with booking via a secure payment gateway.
Log in or register to manage your bookings, view history, and more.
API Endpoints
Method	Endpoint	Description
GET	/api/hotels	Retrieve a list of available hotels
GET	/api/hotels/
Get details of a specific hotel
GET	/api/rooms/
Retrieve rooms for a specific hotel
POST	/api/bookings	(Future) Book a room
POST	/api/users/login	Log in a user
POST	/api/users/register	Register a new user
GET	/api/users/bookings	(Future) Retrieve user bookings
Folder Structure
The project follows a clear separation of concerns, with frontend and backend code organized into separate directories.

Sharerooms/
│
├── backend/          # Backend (Express.js, Node.js)
│   ├── config/       # Configuration (DB, JWT, etc.)
│   ├── models/       # Mongoose models (Hotel, Room, User, Booking)
│   ├── routes/       # API routes
│   ├── controllers/  # Request handlers
│   └── server.js     # Main server file
│
├── frontend/         # Frontend (React.js)
│   ├── public/       # Static files
│   ├── src/          # React components and logic
│   ├── App.js        # Main app file
│   └── index.js      # Entry point
│
└── README.md         # Project documentation


##Project Status
#Development Stage: The project is actively under development.
##Next Milestones:
#Complete booking and payment integration.
#Build user authentication and profile management.
#Implement admin dashboard for hotel management.
#Contributing
#We welcome contributions! Here's how you can contribute:

Fork the repository.
Create a new feature branch (git checkout -b feature/YourFeature).
Commit your changes (git commit -m 'Add your feature').
Push to the branch (git push origin feature/YourFeature).
Open a pull request for review.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
Project Owner: Gaurav
Email: 2k22.cse.2213452@gmail.com
Feel free to reach out for any queries, suggestions, or collaboration opportunities!

