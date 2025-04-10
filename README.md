# ARIZE E-Commerce Website

![Home Page](https://github.com/Urswin-Faro/Module-3_E-Commerce-Arize/blob/6ad1e7e4fda917a7af5aac7c1948c4781b14d742/Screenshot%202025-04-09%20120502.png)

ARIZE is a full-featured e-commerce platform for tech products, providing a seamless shopping experience. Built for the Life Choices assignment by Urswin Faro, Nasra Hendricks, Jemaile Mohamed and Avela Romeo, the project supports product listings, user authentication, and an intuitive checkout flow.

## Table of Contents
- [Live Demo](#live-demo)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Key Features](#key-features)
- [Usage Instructions](#usage-instructions)
- [Potential Improvements](#potential-improvements)
- [Credits](#credits)
- [Author](#authors)

## Live Demo
Click here to view the live demo

## Technologies Used
- Front-end: HTML, CSS, JavaScript (Vanilla.js), Fetch API
- Back-end: Node.js, Express.js
- Database: MySQL
- Other Tools: Git, Bcrypt, JSON Web Token (JWT), Nodemailer, dotenv, CORS

## Setup Instructions
Follow these steps to run ARIZE locally:

1. Prerequisites
- Node.js (version ≥ 14.x)
- MySQL Server
- npm (Node Package Manager)
- Git

2. Clone the Repository
```
git clone https://github.com/GeorgeZa01/ARIZE---E-commerce.git
cd ARIZE---E-commerce
```

3. Install Dependencies
- Navigate to both frontend and backend directories and run:
```
npm install
```

Dependencies include:
```
"bcrypt": "^5.1.1",
"bcryptjs": "^3.0.2",
"cors": "^2.8.5",
"dotenv": "^16.4.7",
"express": "^4.21.2",
"jsonwebtoken": "^9.0.2",
"mysql2": "^3.12.0",
"nodemailer": "^6.10.0"
```

4. Set Up Environment Variables
Create a .env file in the backend directory (refer to .env.example for guidance):
```
DB_HOST=localhost
DB_USER=your_mysql_user
DB_PASS=your_mysql_password
DB_NAME=arize
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
```

5. Database Setup
- Create a database named arize in MySQL.
- Import the SQL schema file if provided.
```
mysql -u root -p arize < database/arize.sql
```

6. Run the Application
- Start backend:
```
npm start
```
- Start frontend (if applicable):
```
npm run dev
```
- Visit http://localhost:3030 in your browser.

## Key Features
- User Registration & Login: Secure authentication using JWT and bcrypt.
- Product Browsing & Search: Search and view product listings.
- Add to Cart & Checkout: Intuitive cart with checkout flow.
- Admin Access: Admin-only access for management tasks.
- Email Integration: Nodemailer for sending emails (e.g., confirmations).
- Environment Configuration: Secure config using dotenv.
- Responsive Layout: Works across desktop and mobile screens.

## Usage Instructions
- Navigate the homepage to explore tech products.
- Register or log in to make purchases.
- Add desired items to the cart and proceed to checkout.
- Use the Products page to connect with the community on Discord.

🛠 Admin Login Credentials (for testing):
```
Email: admin@gmail.com
Password: securepass123
```

## Potential Improvements
- Enhanced product filtering and sorting
- Product reviews and ratings
- Order history and invoice tracking
- Wishlist and save-for-later options
- Integration with third-party payment systems (e.g., Stripe, PayPal)
- Admin dashboard with analytics


## Credits
- Node.js
- Express.js
- MySQL
- Vanilla JavaScript
- JWT
- Nodemailer

## Authors
- Urswin Faro
- Nasra Hendricks
- Jemaile Mohamed
- Avela Romeo

GitHub: https://github.com/Urswin-Faro
