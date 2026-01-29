# Inventory Management System

Inventory Management System is a web-based application developed to manage products efficiently with secure admin authentication.  
This system uses an SQL database for data storage and supports complete CRUD operations for product management.

---

## Features

- Admin Authentication (Login System)
- Product Management (CRUD Operations)
  - Add Product
  - Update Product
  - Delete Product
  - View Products
- SQL Database Integration
- Secure Data Handling
- Custom Designed Frontend UI
- Admin Dashboard with Sidebar
- Responsive Design

---

## Technologies Used

### Backend:
- Node.js 

### Database:
- SQL (MySQL)

### Frontend:
REact.js

---

## Admin Authentication

- Admin login system implemented using SQL database.
- Credentials are verified from database.
- Only authenticated admin can access dashboard.
- Unauthorized users cannot perform CRUD operations.

---

## Database Tables

### Admin Table:
- id  
- username  
- password  

### Products Table:
- id  
- product_name  
- price  
- quantity  
- category  

---

## How to Run Project

1. Clone repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
