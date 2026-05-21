# 🧵 Fabric Management System

A full-stack multi-platform system for managing fabric sales, orders, and delivery operations.

<div align="center">

### 🌐 Three Integrated Platforms

| 📱 User Mobile App | 🚚 Delivery Mobile App | 🖥️ Admin Web Dashboard |
|:---:|:---:|:---:|
| Browse, order & track | Manage & deliver orders | Analytics & administration |

</div>

---

## 🚀 Overview

Fabric Management System is a complete solution designed to handle the entire lifecycle of fabric orders — from browsing products to delivery and analytics.

It provides a seamless experience for **users**, efficient tools for **delivery personnel**, and powerful insights for **administrators**.

---

## 🧩 System Architecture

```
┌─────────────────┐    ┌──────────────────────┐    ┌─────────────────┐
│  📱 User App    │    │  🔥 Firebase Backend  │    │  🖥️ Admin Web   │
│   (Flutter)     │◄──►│  Auth + Firestore     │◄──►│   Dashboard     │
└─────────────────┘    │  + FCM Notifications  │    └─────────────────┘
┌─────────────────┐    └──────────────────────┘
│ 🚚 Delivery App │◄──►         ▲
│   (Flutter)     │       Google Maps
└─────────────────┘
```

---

## ✨ Key Features

<details>
<summary><b>👤 User Mobile Application</b></summary>

- 🛍️ Browse products and categories
- ❤️ Add to favorites
- 🛒 Add to cart and place orders
- 🎯 View offers and discounts
- 📦 Track order status: Shipped → Out for delivery → Delivered
- 📍 Select delivery location using Google Maps
- 🔔 Real-time notifications (FCM) for order updates & new offers
- ⭐ Review & rating system
- 🔐 Authentication: Email/Password, Google Sign-In, Email Verification

</details>

<details>
<summary><b>🚚 Delivery Mobile Application</b></summary>

- 📋 View assigned orders
- 🔄 Update order status in real-time
- 📍 View customer location on Google Maps
- 🗺️ Track route and distance to customer
- 🔔 Send real-time updates to users

</details>

<details>
<summary><b>🖥️ Admin Web Dashboard</b></summary>

- 📦 Manage products (Add / Edit / Delete)
- 🎯 Manage offers & discounts
- 👥 Manage users
- 📋 View all orders
- 📊 Analytics: Total orders, Revenue, Top products, Reviews
- 📤 Export reports to Excel

</details>

---

## 📸 Screenshots

### 👤 User App

<div align="center">

| Login | Home | Offers |
|:---:|:---:|:---:|
| <img src="images/user/login.jpg" width="220"/> | <img src="images/user/home.jpg" width="220"/> | <img src="images/user/offer.jpg" width="220"/> |
| **Login Screen** | **Home Screen** | **Offers & Discounts** |

| Favorites | Cart | Checkout |
|:---:|:---:|:---:|
| <img src="images/user/fav.jpg" width="220"/> | <img src="images/user/cart.jpg" width="220"/> | <img src="images/user/checkout.jpg" width="220"/> |
| **Favorites** | **Shopping Cart** | **Checkout** |

| Order Tracking | Location | Notifications |
|:---:|:---:|:---:|
| <img src="images/user/trackorder.jpg" width="220"/> | <img src="images/user/location.jpg" width="220"/> | <img src="images/user/notificationpage.jpg" width="220"/> |
| **Track Order** | **Delivery Location** | **Notifications** |

</div>

---

### 🚚 Delivery App

<div align="center">

| Waiting Orders | Order Details | Customer Location |
|:---:|:---:|:---:|
| <img src="images/delivery/waiting_oder.jpg" width="220"/> | <img src="images/delivery/order_details.jpg" width="220"/> | <img src="images/delivery/user_location.jpg" width="220"/> |
| **Pending Orders** | **Order Details** | **Customer Location** |

</div>

---

### 🖥️ Admin Dashboard

<div align="center">

| Dashboard Overview | Orders Page | Inventory |
|:---:|:---:|:---:|
| <img src="images/admin/Dashboard.jpg" width="280"/> | <img src="images/admin/orders_page.jpg" width="280"/> | <img src="images/admin/inventory.jpg" width="280"/> |
| **Main Dashboard** | **Orders Management** | **Inventory** |

| Add Fabric | Add Offers | Reviews |
|:---:|:---:|:---:|
| <img src="images/admin/add_fabric.jpg" width="280"/> | <img src="images/admin/add_offers.jpg" width="280"/> 
| **Add New Fabric** | **Manage Offers** |  

| Analytics Chart 1 | Analytics Chart 2 | Analytics Chart 3 |
|:---:|:---:|:---:|
| <img src="images/admin/chart1.jpg" width="280"/> | <img src="images/admin/chart2.jpg" width="280"/> | <img src="images/admin/chart3.jpg" width="280"/> |
| **Revenue Chart** | **Orders Chart** | **Statistics** |

</div>

> 💬 **User Comments Panel**
>
> <div align="center"><img src="images/admin/reviews_comments.jpg" width="600"/></div>

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology |
|:---|:---|
| 📱 Mobile Apps | ![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white) |
| 🌐 Web Dashboard | ![HTML](https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) |
| 🔥 Backend | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black) ![Firestore](https://img.shields.io/badge/Firestore-FFCA28?logo=firebase&logoColor=black) ![FCM](https://img.shields.io/badge/FCM-FFCA28?logo=firebase&logoColor=black) |
| 🗺️ Maps | ![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4?logo=googlemaps&logoColor=white) |
| ⚙️ Workflow | ![Agile](https://img.shields.io/badge/Agile-009688?logoColor=white) ![Scrum](https://img.shields.io/badge/Scrum-6DB33F?logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white) |

</div>

---

## 🔔 Notifications System

Real-time push notifications via **Firebase Cloud Messaging**, triggered on:
- 📦 Order status updates (Shipped / Out for Delivery / Delivered)
- 🎯 New offers & promotions
- 🚚 Delivery updates

---

## 📊 Analytics & Reports

| Metric | Description |
|:---|:---|
| 📈 Monthly Revenue | Track revenue trends over time |
| 📦 Daily Orders | Monitor daily order volumes |
| 🏆 Top Products | Identify best-selling fabric items |
| 📤 Excel Export | Download reports for offline analysis |

---

## 📌 Project Status

> ✅ **Completed** &nbsp;&nbsp;|&nbsp;&nbsp; 🔒 **Source Code: Private**

---

## 👨‍💻 Author

<div align="center">

**Youssef Hesham**

[![GitHub](https://img.shields.io/badge/GitHub-youssef24413-181717?logo=github)](https://github.com/youssef24413)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-youssef--hesham--sayed-0A66C2?logo=linkedin)](https://www.linkedin.com/in/youssef-hesham-sayed/)

</div>
