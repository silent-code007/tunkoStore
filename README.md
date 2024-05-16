# tunkoStore

Overview
Welcome to the Digital & Wall Watches E-commerce Website repository! This project is a full-featured e-commerce application built using the MERN stack (MongoDB, Express.js, React, Node.js). It provides a seamless shopping experience for users looking to purchase digital and wall watches.

Features
User Authentication and Authorization: Secure user registration and login using JWT.
Product Management: Add, edit, delete, and view products with detailed descriptions and high-quality images.
Shopping Cart: Add watches to the cart, modify quantities, and remove items.
Order Management: Complete order processing including order history and status updates.
Payment Integration: Secure payment gateway integration for smooth transactions.
Admin Dashboard: Manage products, orders, and users with an intuitive admin interface.
Responsive Design: Fully responsive design to ensure a great user experience on both desktop and mobile devices.
Technologies Used
Frontend:

React.js for building user interfaces
Redux for state management
React Router for navigation
Axios for API calls
Backend:

Node.js and Express.js for building the server and API
MongoDB for database management
Mongoose for object data modeling (ODM)
Authentication:

JWT (JSON Web Tokens) for secure user authentication
Other Tools:

Stripe/PayPal for payment processing
Cloudinary for image storage
Heroku/Vercel for deployment
Installation
To get a local copy up and running, follow these simple steps:

Prerequisites
Node.js
MongoDB
Installation Steps
Clone the repository

sh
Copy code
git clone https://github.com/your-username/digital-wall-watches-ecommerce.git
cd digital-wall-watches-ecommerce
Install backend dependencies

sh
Copy code
cd backend
npm install
Install frontend dependencies

sh
Copy code
cd ../frontend
npm install
Set up environment variables

Create a .env file in the root of the backend directory and add the following:

makefile
Copy code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
Run the application

In the backend directory, start the server:

sh
Copy code
npm run dev
In the frontend directory, start the React application:

sh
Copy code
npm start
Open your browser and navigate to http://localhost:3000

Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
Distributed under the MIT License. See LICENSE for more information.

Contact
Rajiv Mandal - rajivmandal341@gmail.com

Project Link: https://github.com/silent-code007/tunkoStore
