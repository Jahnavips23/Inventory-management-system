Inventory Management System (MERN Stack)

This is a full-stack Inventory Management System built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to manage products, track stock levels, and maintain inventory records efficiently.

Features

User Login / Signup (JWT Authentication)

Add, Edit, Delete Products

View Product List with Search & Filter

Track Product Quantity (Stock Management)

Low Stock Alerts

Responsive User Interface

Tech Stack

Frontend: React.js, Axios, Bootstrap / Material UI

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

Authentication: JWT + bcrypt

Installation
1. Clone the Repository
git clone https://github.com/your-username/inventory-management.git
cd inventory-management

2. Setup Backend
cd backend
npm install


Create a .env file inside backend/ and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000


Run backend:

npm start

3. Setup Frontend
cd ../frontend
npm install
npm start

Folder Structure
inventory-management/
│
├── backend/      # Node.js + Express API
│   ├── models/
│   ├── routes/
│   └── server.js
│
└── frontend/     # React UI
    ├── src/
    └── public/

API Endpoints
Method	Endpoint	Description
POST	/api/auth/register	Register User
POST	/api/auth/login	Login User
GET	/api/products	Get All Products
POST	/api/products	Create Product
PUT	/api/products/:id	Update Product
DELETE	/api/products/:id	Delete Product
Future Improvements

Admin / Staff Role Management

Export Inventory to Excel / PDF

Barcode Scanner Integration

Advanced Dashboard & Reports

License

This project is licensed under the MIT License.
