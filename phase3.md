# FoodieConnect CRM – Phase 3: Data Modeling & Relationships

## Overview
In Phase 3, we focused on organizing FoodieConnect’s data so that information flows seamlessly across the system. This ensures every record—from restaurants to deliveries—is connected, easy to access, and ready for reporting.

---

## 1. Standard & Custom Objects
- **Restaurant:** Stores partner restaurant details.  
- **Menu Item:** Lists food items offered by restaurants.  
- **Customer:** Tracks customer details and loyalty points.  
- **Order:** Manages all orders placed.  
- **Delivery:** Monitors delivery assignments and status.  
- **Payment:** Records payment information.  
- **Issue (Support Case):** Logs customer complaints or queries.

These objects allow the system to capture all business operations efficiently.

---

## 2. Fields
Key fields were added to each object for clarity and operational needs:
- **Restaurant:** Name, Location, Cuisine Type, Rating  
- **Menu Item:** Name, Price, Availability, Category  
- **Customer:** Name, Email, Loyalty Points  
- **Order:** Order Number, Customer, Total Amount, Status  
- **Delivery:** Delivery Number, Order, Rider, Delivery Status  
- **Payment:** Payment Number, Amount, Payment Method, Payment Date  
- **Issue:** Issue Number, Customer, Status, Issue Type

---

## 3. Record Types & Page Layouts
- **Record Types:** Differentiate types of orders or issues for better organization.  
- **Page Layouts:** Customized by role—Admins see full records; Riders and Support see only relevant info.

This ensures a clean, role-specific view of data.

---

## 4. Compact Layouts
Designed for quick access, especially in the mobile app:
- Restaurant Highlights
- Menu Item Highlights
- Customer Highlights
- Order Highlights
- Delivery Highlights
- Issue Highlights
- Payment Highlights

These layouts display key information at a glance for faster decision-making.

---

## 5. Schema Builder & Relationships
- **Lookup Relationships:** Connect related records, e.g., Menu Items → Restaurant.  
- **Master-Detail Relationships:** Maintain tighter control, e.g., Orders → Menu Items.

Schema Builder provides a visual map of all objects and relationships, making it easy to manage automation, reporting, and dashboards.

---
