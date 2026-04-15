# 🚛 SFMPL TMS v5 — Transport Management System

A modern **Transport Management System (TMS)** built using **HTML + Supabase Backend**, designed to manage full logistics workflows including vehicles, challans, users, and operations.

---

## 📌 Overview

**SFMPL TMS v5** is a complete workflow-based system transformed from **Google Apps Script (v7.1)** into a scalable **Supabase-powered web application**.

It provides role-based access and efficient handling of transport operations in a clean, dashboard-style UI.

---

## ⚙️ Features

### 🔐 Role-Based Access Control

* **SUPERADMIN**

  * Full control (Add / Edit / Delete all data)
* **ADMIN**

  * Full access except delete
  * User management
* **USER**

  * Limited module-based access
  * Read & write permissions

---

### 🚗 Core Modules

* Vehicle Management
* Challan Management
* Dashboard Analytics
* User Management
* Workflow Tracking System

---

### 📊 Dashboard

* Total Vehicles Count
* Total Challans
* Unpaid Challans
* Real-time stats using Supabase queries

---

### 🗄️ Database (Supabase)

* Fully structured SQL schema
* Scalable backend
* Real-time data operations

---

## 🏗️ Project Structure

SFMPL_TMS_v5/
│
├── SFMPL_TMS_v5.html       # Main frontend UI
├── SFMPL_TMS_v5_SCHEMA.sql # Database schema for Supabase

---

## 🚀 Setup Instructions

### 1️⃣ Supabase Setup

1. Go to Supabase
2. Create a new project
3. Open **SQL Editor**
4. Run the provided schema file:
   SFMPL_TMS_v5_SCHEMA.sql

---

### 2️⃣ Configure Project

Open `SFMPL_TMS_v5.html` and update:

const SUPABASE_URL = "YOUR_SUPABASE_URL";
const SUPABASE_ANON_KEY = "YOUR_SUPABASE_ANON_KEY";

---

### 3️⃣ Run Project

* Open the HTML file in your browser
* Or deploy using:

  * GitHub Pages
  * Netlify
  * Vercel

---

## 🔑 Default Login

Username: superadmin
Password: superadmin123

---

## 🎨 UI Highlights

* Clean GitHub-style UI
* Sidebar navigation system
* Responsive layout
* Color-coded status indicators

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Supabase
* **Database:** PostgreSQL (via Supabase)

---

## 📈 Future Improvements

* API Integration (RTO / Challan APIs)
* Mobile Responsive Enhancements
* Advanced Reporting & Export (PDF/Excel)
* Notification System
* Multi-branch Support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch
3. Commit changes
4. Submit a pull request

---

## 📄 License

This project is for internal/business use. Customize as needed.

---

## 👨‍💻 Author

**Ankush Singh**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
