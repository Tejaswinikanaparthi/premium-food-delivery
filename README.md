# Food Delivery Platform

This project is a full-stack food delivery application developed using React.js, Node.js, Express.js, and MySQL. The application allows users to browse food items, register and log in securely, manage orders, and access different functionalities based on user roles.

The project is divided into frontend and backend modules. The frontend contains the user interface pages, while the backend handles APIs, database operations, authentication, and server-side logic.

## Features

- User registration and login
- JWT-based authentication
- Product and food item management
- Cart and order handling
- Role-based access for customers and owners
- REST API integration
- Responsive user interface
- MySQL database support

## Technologies Used

### Frontend
- React.js
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MySQL

## Project Structure

```bash
Food-Delivery-Platform/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── db.js
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
│
├── frontend/
│
├── css/
├── js/
│
├── customer.html
├── login.html
├── owner.html
├── register.html
│
├── .gitignore
└── README.md
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/food-delivery-platform.git
```

## Backend Setup

Move to the backend folder:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Start the backend server:

```bash
npm start
```

## Frontend Setup

Move to the frontend folder:

```bash
cd frontend
```

Install required packages:

```bash
npm install
```

Run the frontend application:

```bash
npm start
```

## Environment Variables

Create a `.env` file inside the backend folder and add:

```env
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=food_delivery
JWT_SECRET=secret_key
```

## Database Setup

Create the database in MySQL:

```sql
CREATE DATABASE food_delivery;
```

Import the required tables into the database before running the project.

## Pages Included

- `login.html` – User login page
- `register.html` – User registration page
- `customer.html` – Customer dashboard
- `owner.html` – Owner dashboard

## Future Enhancements

- Online payment integration
- Real-time order tracking
- Notification system
- Admin dashboard
- Review and rating feature

## Author

Tejaswini Kanaparthi
