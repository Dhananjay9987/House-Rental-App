#  House Rental App

A complete full-stack House Rental Web App built with **React**, **Node.js**, **Express**, and **MongoDB**. The app supports multi-role access for **Owners** and **Renters**, with secure **JWT authentication**, **property listings**, **inquiries**, and real-time UI updates.

---

##  Live Demo
http://13.222.139.163

##  Features
- User Registration & Login
- Property Listings
- JWT Authentication
- Responsive UI

##  Tech Stack
- React.js
- Node.js
- Express.js
- MongoDB
- AWS EC2
- Nginx
- PM2

##  Deployment
- Backend running on AWS EC2
- Frontend served via Nginx
- MongoDB Atlas used as cloud database
- Reverse proxy configured for API routing

##  How to Run Locally

### Backend
cd backend  
npm install  
npm start  

### Frontend
cd frontend  
npm install  
npm run dev  

##  Tech Stack

**Frontend**:  
- React  
- React Router  
- Context API  
- Axios  

**Backend**:  
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JWT (Access + Refresh Tokens)  
- Bcrypt  

**Other Tools**:  
- Render (Deployment)  
- Cloudinary / Local Image Handling  
- Postman (Testing APIs)

---

##  Features Implemented

###  Authentication & Authorization
- User Registration & Login
- Passwords hashed using bcrypt
- JWT-based authentication with **access & refresh token flow**
- Role-based access control (Owner, Renter)

###  Property Management
- Owners can:
  - Create property listings
  - Edit and delete their own properties
  - View all their listed properties
- Renters can:
  - View available properties
  - Send inquiries to owners
  - View property details in **read-only mode**

###  Inquiries System
- Renters can send inquiries on any property
- Owners can view, approve, or reject inquiries
- Inquiry status managed via enums (`pending`, `approved`, `rejected`)

###  Smart Access Control
- Only owners can edit/delete their own listings
- Renters and guests get read-only access
- Routes protected via middleware based on JWT & roles

###  RESTful APIs
- Full CRUD operations for properties
- Role-specific API access
- Inquiry creation and approval/rejection logic

## 📸 UI Screens
-  Login / Register
-  Home Page (Property listings)
-  Owner Dashboard (My Properties)
-  Add / Edit Property
-  Property Details (read-only or editable)
-  Inquiry Form & Inquiry Management

