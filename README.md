# Laravel Ecommerce

# 🛍️ Laravel E-commerce Project

> A powerful and responsive E-commerce platform built with **Laravel 9** and **Blade Template**.

---

## 🛠️ Tech Stack & Environment

| Component | Specification |
| :--- | :--- |
| **Framework** | Laravel ^9.11 |
| **Language** | PHP ^8.0.2 (Tested on 8.2.12) |
| **Database** | MariaDB / MySQL (10.4.32) |
| **Auth System** | Laravel UI (Bootstrap/Vue) |

---

## 🚀 Quick Installation Guide

Follow these simple steps to run this project locally on your machine:

### 1. Clone the project and Install Dependencies
```bash
composer install
npm install
```

### 2. Environment Configuration
* Create a `.env` file by copying `.env.example`
* Configure your database credentials:
```env
DB_DATABASE=simple_ecommerce
DB_USERNAME=root
DB_PASSWORD=
```

### 3. Database Migration & Key Generate
```bash
php artisan key:generate
php artisan migrate --seed
```

### 4. Run Application
```bash
php artisan serve
```
> Now open your browser and visit: `http://127.0.0.1:8000`

---

## 📦 Core Features Implemented

* 🗂️ **Category Management:** Dynamic product categorization (e.g., iPhone Zone, Samsung Zone).
* 🏷️ **Product Catalog:** Manage inventory, dynamic stock levels, pricing, and descriptions.
* 🛒 **Order Processing:** Automated `order_code` generation with tracking and complete order details.
