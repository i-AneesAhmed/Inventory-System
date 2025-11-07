# 🏪 Inventory Management System (Tkinter + MySQL)

This project is a **desktop-based Inventory Management System** built using **Python (Tkinter GUI)** and **MySQL database**.  
It provides an intuitive interface for managing employees, suppliers, product categories, product inventory, and sales operations within an organization.

---

## 📋 Table of Contents
1. [Overview](#-overview)
2. [Key Features](#-key-features)
3. [Module Descriptions](#-module-descriptions)
   - [1. Dashboard](#1-dashboard)
   - [2. Employee Management Module](#2-employee-management-module)
   - [3. Supplier Management Module](#3-supplier-management-module)
   - [4. Product Management Module](#4-product-management-module)
   - [5. Sales Management Module](#5-sales-management-module)
   - [6. Category Management Module](#6-category-management-module)
4. [Database Design](#-database-design)
5. [Technology Stack](#-technology-stack)
6. [Installation Guide](#-installation-guide)
7. [Usage Instructions](#-usage-instructions)
8. [Future Enhancements](#-future-enhancements)
9. [Author](#-author)

---

## 🧩 Overview
The **Inventory Management System** is designed to efficiently handle and monitor all essential business resources — including employees, suppliers, categories, products, and sales transactions — through a centralized desktop interface.  
It ensures streamlined business processes, accuracy, and improved decision-making through real-time data tracking.

---

## ✨ Key Features
- 🎨 **User-friendly Tkinter GUI**
- 💾 **MySQL Database Integration**
- 👨‍💼 **Employee Record Management**
- 🏭 **Supplier Tracking**
- 📦 **Product and Category Management**
- 💰 **Sales Processing and History**
- 🔄 **CRUD Operations (Add, Update, Delete, Fetch)**
- 📊 **Dashboard Summary and Navigation**
- ⚙️ **Error Handling and Validation**

---

## 🧱 Module Descriptions

### **1. Dashboard**
- Main control hub of the system.
- Provides navigation to Employees, Suppliers, Categories, Products, and Sales.
- Clean layout using Tkinter Frames.
- Includes logout, exit, and key statistic sections.

---

### **2. Employee Management Module**
- Handles **employee record management** with Add, Update, Delete, and Fetch options.
- Stores:
  - Employee ID
  - Name
  - Contact
  - Email
  - Gender
  - Role
- Displays data using Treeview and validates all entries.

---

### **3. Supplier Management Module**
- Manages supplier information:
  - Supplier ID
  - Name
  - Company
  - Contact Info
  - Address
- Linked with product and category modules.
- Full CRUD functionality via MySQL.

---

### **4. Product Management Module**
- Core of the inventory system.
- Stores:
  - Product ID
  - Product Name
  - Category
  - Supplier
  - Quantity
  - Price
- Tracks stock automatically when sales occur.
- Supports search and filtering by category or supplier.

---

### **5. Sales Management Module**
- Handles all **sales transactions**.
- Tracks:
  - Sale ID
  - Product Sold
  - Quantity
  - Price
  - Date & Time
- Updates stock dynamically.
- Shows sales history in a Treeview table.

---

### **6. Category Management Module**
- Organizes products into **categories**.
- Allows:
  - Add, Delete, and View Categories
  - Manage descriptions for each
- Uses MySQL table `category_data`.
- Displays interactive Treeview with category records.
- Optional category image support and modern form UI.

---

## 🗃️ Database Design
**Database Name:** `inventory_system`

**Tables:**
- `employee_data`
- `supplier_data`
- `product_data`
- `category_data`
- `sales_data`

Each table includes:
- Primary Key (Auto Increment)
- Unique constraints for data integrity
- Foreign Key relationships where necessary

---

## 💻 Technology Stack
| Component | Technology Used |
|------------|-----------------|
| **Programming Language** | Python 3.x |
| **GUI Framework** | Tkinter |
| **Database** | MySQL |
| **Connector** | PyMySQL |
| **IDE (Recommended)** | VS Code / PyCharm |
| **Supported OS** | Windows / Linux / macOS |

---

## ⚙️ Installation Guide

Follow these steps carefully to install and run the project:

### **1️⃣ Install Python**
- Download and install **Python 3.x** from the official site:  
  🔗 [https://www.python.org/downloads/](https://www.python.org/downloads/)
- During installation, **check the box** that says:  
  ✅ *“Add Python to PATH”*

---

### **2️⃣ Install MySQL**
- Download and install **MySQL Community Server**:  
  🔗 [https://dev.mysql.com/downloads/](https://dev.mysql.com/downloads/)
- Set the following credentials during setup:
  - **Username:** `root`
  - **Password:** `anees123` (or your own)
- Note these credentials for later use.

---

### **3️⃣ Create Database**
Open the **MySQL Command Line** or **Workbench**, then run:
```sql
CREATE DATABASE inventory_system;
