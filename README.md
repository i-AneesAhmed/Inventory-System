# 🏪 Inventory Management System (Tkinter + MySQL)

A **desktop-based Inventory Management System** built with **Python (Tkinter GUI)** and **MySQL**, designed for efficient management of employees, suppliers, products, categories, and sales operations.

---

## 📋 Table of Contents
1. [Overview](#overview)
2. [Key Features](#key-features)
3. [Modules](#modules)
4. [Database Design](#database-design)
5. [Tech Stack](#tech-stack)
6. [Installation Guide](#installation-guide)
7. [Usage](#usage)
8. [Future Enhancements](#future-enhancements)
9. [Author](#author)

---

## 🧩 Overview
This system centralizes inventory management with CRUD operations for all entities — employees, suppliers, products, categories, and sales — offering an easy-to-use interface and MySQL-backed data accuracy.

---

## ✨ Key Features
- 🧭 Centralized Dashboard  
- 👨‍💼 Employee & Supplier Management  
- 📦 Product & Category Tracking  
- 💰 Sales Recording & Stock Updates  
- 🔄 Add / Update / Delete / Search  
- 🧱 MySQL Integration with Error Handling  

---

## 🧱 Modules

### 🏠 Dashboard
Main navigation hub linking all modules — clean layout with Tkinter Frames.

### 👨‍💼 Employee Module
Manage employee details: ID, Name, Contact, Email, Role. Includes Add, Update, Delete, View.

### 🏭 Supplier Module
Store supplier info: ID, Company, Contact, Address. Linked to product data.

### 📦 Product Module
Add and manage products with category, supplier, quantity, and price. Auto-stock updates on sales.

### 💰 Sales Module
Record product sales, quantities, total price, and date. Maintains transaction history.

### 🗂️ Category Module
Add, delete, and view categories with descriptions. Supports images and live data view.

---

## 🗃️ Database Design
**Database:** `inventory_system`

**Tables:**
`employee_data`, `supplier_data`, `product_data`, `category_data`, `sales_data`

Each has:
- Auto-increment primary key  
- Unique constraints for integrity  
- Relationships where necessary  

---

## 💻 Tech Stack
| Component | Technology |
|------------|-------------|
| Language | Python 3.x |
| GUI | Tkinter |
| Database | MySQL |
| Connector | PyMySQL |
| IDE | VS Code / PyCharm |
| OS | Windows / Linux / macOS |

---

## ⚙️ Installation Guide

1️⃣ **Install Python 3.x**  
➡️ [https://www.python.org/downloads/](https://www.python.org/downloads/)  
✔ Check “Add Python to PATH”

2️⃣ **Install MySQL**  
➡️ [https://dev.mysql.com/downloads/](https://dev.mysql.com/downloads/)  
Use credentials:  
`root` / `anees123` (or your own)

3️⃣ **Create Database**
```sql
CREATE DATABASE inventory_system;
