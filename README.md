# DB_ER_Diagram
Instagram Thrift Creator Store

📦 Thrift & Handmade Store ER Diagram
📌 Overview

This project contains an ER Diagram for an Instagram-based store selling:

Thrift items (unique, single piece)
Handmade products (multiple stock)

It models product management, orders, payments, and shipping.

🧩 Entities
Customer
Product
Product_Variant
Order
Order_Item (junction table)
Payment
Shipping

🔗 Key Relationships
One Customer → Many Orders
One Order → Many Order_Items
One Product → Many Variants
One Order_Item → One Product Variant
One Order → Payment & Shipping

🎯 Key Features
Supports both thrift (single stock) and handmade (multiple stock)
Uses Product_Variant for size, color, condition
Handles many-to-many with Order_Item
Tracks payment & delivery status
🖼️ Diagram

See er-diagram.png

👨‍💻 Author

Mahesh Dhondge
