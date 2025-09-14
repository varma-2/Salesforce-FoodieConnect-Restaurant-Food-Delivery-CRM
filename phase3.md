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
Designed for quick access, especially in the mobile app. Key screenshots:  

![Restaurant Compact Layout](Salesforce-FoodieConnect-Restaurant-Food-Delivery-CRM/images/restaurent-compact-layout.png)  
*Restaurant Highlights*  

![Menu Item Compact Layout](Salesforce-FoodieConnect-Restaurant-Food-Delivery-CRM/images/menu-item-compact-layout.png)  
*Menu Item Highlights*  

![Customer Compact Layout](Salesforce-FoodieConnect-Restaurant-Food-Delivery-CRM/images/customer-compact-layout.png)  
*Customer Highlights*  

![Order Compact Layout](Salesforce-FoodieConnect-Restaurant-Food-Delivery-CRM/images/order-compact-layout.png)  
*Order Highlights*  

![Delivery Compact Layout](Salesforce-FoodieConnect-Restaurant-Food-Delivery-CRM/images/delivery-compact-layout.png)  
*Delivery Highlights*  

![Payment Compact Layout](Salesforce-FoodieConnect-Restaurant-Food-Delivery-CRM/images/Payment-compact-layout.png)  
*Payment Highlights*  

These layouts display key information at a glance for faster decision-making.

---

## 5. Schema Builder & Relationships
- **Lookup Relationships:** Connect related records, e.g., Menu Items → Restaurant.  
- **Master-Detail Relationships:** Maintain tighter control, e.g., Orders → Menu Items.

Visual map of objects and relationships:  

![Schema Builder](Salesforce-FoodieConnect-Restaurant-Food-Delivery-CRM/images/schema-builder.png)  
*Schema Builder view of all objects and relationships*  

---
