# 🏪 Inventory Management System (Tkinter + MySQL)

A lightweight **desktop-based inventory system** built with **Python (Tkinter)** and **MySQL**, for managing employees, suppliers, products, categories, and sales.

---

## 📋 Overview
This system simplifies stock and record management with CRUD operations and a clear dashboard UI. It’s ideal for academic or small business use.

---

## ✨ Key Features
- 🧭 Centralized Dashboard  
- 👨‍💼 Manage Employees & Suppliers  
- 📦 Add / Update / Delete Products & Categories  
- 💰 Track Sales & Update Stock Automatically  
- 💾 MySQL Database Integration  

---

## 🧱 Modules
| Module | Description |
|---------|--------------|
| **Dashboard** | Main control hub for navigation |
| **Employee** | Manage staff records |
| **Supplier** | Track suppliers and companies |
| **Product** | Manage products, stock, and pricing |
| **Sales** | Record transactions and update stock |
| **Category** | Group products by category |

---

## 🗃️ Database
**Database Name:** `inventory_system`  
**Tables:** `employee_data`, `supplier_data`, `product_data`, `category_data`, `sales_data`  
Each table uses a primary key and enforces data integrity.

---

## 💻 Tech Stack
| Component | Technology |
|------------|-------------|
| Language | Python 3.x |
| GUI | Tkinter |
| Database | MySQL |
| Connector | PyMySQL |

---

## ⚙️ Installation Guide
1️⃣ Install **Python 3.x** → [python.org](https://www.python.org/downloads/)  
2️⃣ Install **MySQL Server** → [dev.mysql.com](https://dev.mysql.com/downloads/)  
3️⃣ Create Database:
```sql
CREATE DATABASE inventory_system;
