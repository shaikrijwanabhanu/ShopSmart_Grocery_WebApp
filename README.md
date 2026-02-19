# 🛒 ShopSmart -- Full Stack Grocery Web Application

![ShopSmart
Banner](https://plus.unsplash.com/premium_photo-1683133442375-501c81500fd8?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8Z3JvY2VyeSUyMGFwcHxlbnwwfHwwfHx8MA%3D%3D)

------------------------------------------------------------------------

## 📖 Overview

ShopSmart is a full-stack grocery web application built using the MERN architecture (MongoDB, Express.js, React.js, Node.js). The application allows users to browse grocery products, manage their shopping cart, and place orders. Administrators can manage products, categories, and user orders through a dedicated admin panel.

This project demonstrates full-stack development, RESTful API integration, authentication, and role-based access control.

------------------------------------------------------------------------

## 🚀 Live Tech Stack

### 🔹 Frontend
- React.js
- React Router DOM
- Bootstrap & Styled Components
- Axios
- Context API

### 🔹 Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- REST APIs

------------------------------------------------------------------------

## ✨ Key Features

### 👤 User Features
- User Registration & Login
- Secure Authentication
- Browse Products by Categories
- Add / Remove Products from Cart
- Place Orders
- View Order History
- Logout Confirmation

### 🛠️ Admin Features
- Admin Login
- Add New Products
- Update / Delete Products
- Manage Categories
- View All User Orders
- Monitor Inventory (Stock Management)

------------------------------------------------------------------------

## 🏗️ System Architecture

The application follows a client-server architecture:

- React frontend communicates with Express backend via REST APIs.
- Backend handles business logic and database interactions.
- MongoDB stores users, products, orders, and categories.

------------------------------------------------------------------------

## 📂 Project Structure

```
ShopSmart/ 
│ 
├── Backend/ 
│ ├──db/
│ ├──index.js/
│ ├──package.json
│
├── Frontend/ 
│ ├──public/
│ ├──src/
│ ├──package.json
│
└── README.md
```

------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/ShopSmart-Grocery-WebApp.git
cd ShopSmart-Grocery-WebApp
```

### 2️⃣ Start MongoDB

Make sure MongoDB is running:

```bash
mongod
```

### 3️⃣ Run Backend

```bash
cd Backend
npm install
node index.js
```

Backend runs on: 

```arduino
http://localhost:5100
```

### 4️⃣ Run Frontend

Open new terminal:

```bash
cd Frontend
npm install
npm start
```

Frontend runs on: 

```arduino
http://localhost:3000
```

------------------------------------------------------------------------

## 🔐 Role-Based Access Control

| Role  | Permissions                                |
| ----- | ------------------------------------------ |
| User  | Browse products, Add to cart, Place orders |
| Admin | Manage products, Categories, Orders        |

------------------------------------------------------------------------

## 🗄️ Database Collections

-   Users
-   Products
-   Categories
-   Orders

------------------------------------------------------------------------

## 📸 Screenshots

### 🏠 Home Page

![Home Page
Screenshot](Screenshots/homepage.png)

### 🔐 Login Page

![Login Page
Screenshot](Screenshots/loginpage.png)

### 🛍️ Product Listing

![Products
Screenshot](Screenshots/products.png)

### 🛒 Cart Page

![Cart
Screenshot](Screenshots/cartpage.png)

### 🛠️ Admin Dashboard

![Admin Dashboard
Screenshot](Screenshots/admindashboard.png)

------------------------------------------------------------------------

## 🧪 Testing

-   Manual testing performed for authentication flow
-   API endpoints tested using Postman
-   Verified frontend-backend integration   

------------------------------------------------------------------------

## 🚀 Future Enhancements

-   Online Payment Integration (Stripe)
-   Order Tracking System
-   Email Notifications
-   Advanced Search & Filters
-   Product Reviews & Ratings

------------------------------------------------------------------------

## 👩‍💻 Author

Harika Devi
B.Tech -- Computer Science & Engineering
Full Stack Developer (MERN)

------------------------------------------------------------------------

## 📄 License

This project is developed for academic and portfolio purposes.
