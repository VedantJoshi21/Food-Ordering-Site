🍔 Food Retail Ordering Website

A full-stack food retail ordering web application inspired by platforms like Zomato, built using Angular, .NET Core Web API, and SQL Server.
The application allows users to browse available food items, add them to a cart, and place orders seamlessly.

🚀 Features
👤 User Features

View available food items and restaurants

Search and filter food items

Add items to cart

Update item quantity in cart

Remove items from cart

Place food orders

View order summary

🛠 Admin Features (Optional / Extendable)

Add, update, and delete food items

Manage restaurant listings

View placed orders

🧱 Tech Stack

Frontend
- Angular
- TypeScript
- HTML5, CSS3
- Bootstrap / Angular Material (if used)

Backend
- .NET Core Web API
- RESTful APIs
- Entity Framework Core

Database
- SQL Server

Relational schema for Users, Food Items, Cart, Orders
🏗 Project Architecture
FoodOrderingApp/
│
├── Frontend (Angular)
│   ├── Components
│   ├── Services
│   ├── Models
│   └── Routing
│
├── Backend (.NET Core Web API)
│   ├── Controllers
│   ├── Models
│   ├── Services
│   ├── Repositories
│   └── Data (DbContext)
│
└── Database
    └── SQL Server Tables
