# Food Delivery Platform

This project is a full-stack food delivery application developed using Node.js, Express.js, MySQL, HTML, CSS, and JavaScript. The application allows users to register, log in, browse food items, and manage orders through a simple and responsive interface.

The backend handles authentication, routing, database connectivity, and API operations, while the frontend is built using HTML, CSS, and JavaScript.

## Features

- User registration and login
- JWT-based authentication
- Food item and order management
- Customer and owner modules
- REST API integration
- Responsive frontend design
- MySQL database connectivity

## Technologies Used

### Frontend
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

Run the server:

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

Import the required tables before starting the project.

## Pages Included

- `login.html` – Login page
- `register.html` – Registration page
- `customer.html` – Customer interface
- `owner.html` – Owner interface

## Future Improvements

- Payment gateway integration
- Live order tracking
- Admin panel
- Product reviews and ratings
- Email notifications

## Author

Tejaswini Kanaparthi 
LokeshReddy Goli
