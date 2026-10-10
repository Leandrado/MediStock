# MediStock

A backend-focused project for managing a **drugstore system**, built with **Python**.


## How it Works ⚙️
User can acess the platform and purchase products from the drugstore. All data is provided by a **REST API**, built with **Flask** and managed using **SQLAlchemy** for database operations.


## Features 🛠️
* Authentication (Login)
* Product management
* Stock control
* Order system
* Sales tracking (Earnings)
* Customer management
* Employee management


## Tecnologies 💻
### Backend
* Python 3.12+
* Flask
* REST API

### Frontend
* HTML5
* CSS3
* JavaScript
* React
* Vite

### Data
* SQLAlchemy
* SQLite (development)



## User Roles
### Customer
* Purchase products
* Login/Logout

### Employee
* Process sales
* Manage products

### Stock Manager
* Control inventory
* Restock products


## Aditional Features
* Prescription-required products control
* Customer credit system


## Structure 📁
```
MediStock/

backend/
│
├── app/
│   ├── __init__.py
│   ├── extensions.py
│   │
│   ├── routes/
│   │   ├── auth_routes.py
│   │   ├── customer_routes.py
│   │   ├── employee_routes.py
│   │   ├── product_routes.py
│   │   ├── sales_routes.py
│   │   └── purchase_routes.py
│   │
│   ├── services/
│   │   ├── auth_service.py
│   │   ├── customer_service.py
│   │   ├── product_service.py
│   │   ├── sales_service.py
│   │   └── purchase_service.py
│   │
│   ├── models/
│   │   ├── customer_model.py
│   │   ├── employee_model.py
│   │   ├── company_model.py
│   │   ├── product_model.py
│   │   ├── sale_model.py
│   │   ├── sale_item_model.py
│   │   ├── purchase_model.py
│   │   └── purchase_item_model.py
│   │
│   ├── schemas/
│   │   ├── customer_schema.py
│   │   ├── product_schema.py
│   │   ├── sale_schema.py
│   │   └── purchase_schema.py
│   │
│   ├── core/
│   │   ├── config.py
│   │   └── security.py
│   │
│   └── database/
│       └── connection.py
│
├── main.py
├── .env
├── requirements.txt
└── .gitignore

frontend/
│
├── index.html
├── public/
│   └── logo.svg
│
└── src/
    ├── main.jsx
    ├── App.jsx
    │
    ├── routes/
    ├── pages/
    └── components/
```