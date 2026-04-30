# Kasi Distributors – Product Design Assessment

## Overview

This project was created as part of a Product Designer assessment for Kasi Distributors, a small wholesale business supplying household goods to spaza shops.

The goal of this solution is to address a key business challenge:

> The current manual system (phone orders + spreadsheets + manual delivery tracking) is limiting the company’s ability to scale.

To solve this, I designed and built **two separate but connected systems**:

* A **Customer-Facing Ordering System**
* An **Admin (Operations) System**

These systems reflect the real-world roles within the business and are designed to reduce operational friction while enabling growth.

---

## Why Two Separate Systems?

The decision to separate the system into **Admin** and **Customer-facing** experiences is intentional and based on how the business operates.

### 1. Different Users Have Different Needs

#### Customer (Spaza Shop Owner)

Customers only want to:

* Browse products
* Place orders quickly
* Track orders
* Reorder frequently

They do **not** need access to:

* Inventory management
* Sales data
* Internal operations

---

#### Admin (Mpumi)

Mpumi is responsible for:

* Managing all incoming orders
* Tracking inventory
* Handling deliveries
* Recording payments

She needs:

* A structured dashboard
* Clear visibility of orders and stock
* Tools to reduce manual work

---

### Key Insight

> A single system for both users would increase complexity and confusion.

By separating the experiences:

* Customers get a **simple and fast ordering flow**
* Admin gets a **powerful operations dashboard**

---

## Customer-Facing System (Spaza Shop Owner)

### Purpose

To replace phone-based ordering with a **simple, mobile-friendly digital experience**

### Key Features

* User authentication (Sign up, Login, 2FA simulation)
* Product browsing (Food, Drinks, Household items)
* Add to cart and checkout
* Order confirmation
* Order history tracking
* Quick “Reorder” functionality

### Design Focus

* Mobile-first experience
* Minimal steps to complete an order
* Large, clear UI for low-tech users
* Speed and simplicity

---

## Admin System (Operations Dashboard)

### Purpose

To replace spreadsheet-based operations with a **centralised management system**

### Key Features

* Dashboard overview (sales, orders, stock alerts)
* Order management (update status, track progress)
* Inventory tracking (stock levels, low stock alerts)
* Payment tracking (cash vs card)
* Customer view simulation (to assist customers if needed)

### Design Focus

* Clear data visibility
* Reduced manual tracking
* Structured workflow for daily operations

---


## Key UX Decisions

### 1. Separation of Roles

Each user sees only what they need, reducing confusion and errors.

---

### 2. Mobile-First Customer Experience

Spaza shop owners are likely to use mobile devices, so the system is responsive.

---

### 4. Admin Dashboard Focus

Instead of spreadsheets, the admin now works from a structured interface that:

* Reduces cognitive load
* Improves accuracy
* Saves time

---

## Technology Used

* HTML5
* CSS3
* React (for component-based structure)
* Basic Bootstrap (for layout only)

The system was intentionally kept **simple and lightweight** to reflect an MVP (Minimum Viable Product) approach.

---


