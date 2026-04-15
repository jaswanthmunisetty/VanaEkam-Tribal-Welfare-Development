# 🌿 VanaEkam — Empowering Tribal Economies Through Technology

**VanaEkam** is a full-stack platform designed to connect **tribal communities, donors, and buyers** — enabling direct support, transparent donations, and sustainable commerce.

This is not just an app.
It’s an attempt to **fix broken economic pipelines**.

---

## 🚨 The Problem

Tribal communities face:

* Limited market access
* Exploitation by middlemen
* Lack of direct financial support
* Zero transparency in donation systems

Result → Skilled artisans stay underpaid and invisible.

---

## 💡 The Solution

**VanaEkam** creates a unified ecosystem where:

* Donors can contribute securely
* Vendors can sell directly
* Buyers can support ethical products

No middlemen. No opacity. Just direct impact.

---

## ✨ Key Features

### 💳 Donations System

* One-time & recurring donations
* Integrated with **Razorpay** for secure transactions
* Transparent tracking of contributions

### 🛍️ E-Commerce Platform

* Product listings from tribal vendors
* Cart, checkout, and order management
* Seamless buying experience

### 🔐 Authentication & Security

* JWT-based authentication (access + refresh tokens)
* Role-based access: **Donor | Vendor | Admin**
* Password hashing with bcrypt

### 📦 Vendor Dashboard

* Manage products and inventory
* Track orders and earnings

### 🛠️ Admin Panel

* Approve/reject product listings
* Monitor donations and transactions
* Manage users and platform activity

### 📊 Tracking & Reports

* Order history and receipts
* Donation tracking for transparency
* Impact visibility for users

---

## 🏗️ System Architecture

```id="arch1"
Client (React)
   ↓
Server (Node.js + Express)
   ↓
MongoDB Database
   ↓
Razorpay (Payments API)
```

* **Frontend:** UI, routing, state management
* **Backend:** REST APIs, authentication, payment handling
* **Database:** Users, products, orders, donations
* **Payments:** Razorpay integration + webhooks

---

## 🛠️ Tech Stack

* **Frontend:** React, React Router
* **State Management:** Redux / Context API
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose)
* **Authentication:** JWT + bcrypt
* **Payments:** Razorpay API

---

## ⚡ Getting Started

### Prerequisites

* Node.js (v16+)
* MongoDB (Local / Atlas)
* Razorpay Account

### Installation

```bash id="inst1"
git clone https://github.com/your-username/vanaekam.git
cd vanaekam

cd server && npm install
cd ../client && npm install
```

### Run the Application

```bash id="run1"
# Backend
cd server && npm run dev

# Frontend
cd client && npm start
```

---

## 🌍 Impact Vision

VanaEkam aims to:

* Support **tribal artisans with direct income**
* Promote **ethical and conscious consumerism**
* Build **trust through transparent donations**
* Preserve **traditional craftsmanship**

Every transaction contributes to **real-world impact**, not just platform activity.

---

## 🔒 License

This project is licensed under the **MIT License**.

---

## 🧠 Why This Project Stands Out

Most e-commerce apps focus on profit.
Most donation apps lack transparency.

**VanaEkam combines both — with purpose.**
