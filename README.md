# 🛍️ E-Commerce Inventory & Order Management System  

## 📘 Overview  
This project implements a **Relational Database Schema** for a complete **E-Commerce Inventory & Order Management System**.  
It is designed to efficiently manage **users, customers, suppliers, products, orders, inventory, payments**, and more, following **database normalization** and **referential integrity** principles.

The database supports key e-commerce operations including:
- Product and supplier management  
- Inventory tracking across multiple warehouses  
- Order and payment processing  
- Review system for customer feedback  
- Automated inventory adjustments via triggers  

## 📂 Repo Structure

```
📦 E-Commerce-Inventory-Order-Management-System
│
├── 📁 SQL
│ └── 
│
├── 📁 CSV
│ ├── customers.csv # Sample customer data
│ ├── suppliers.csv # Sample supplier data
│ ├── products.csv # Product catalog data
│ ├── orders.csv # Example order dataset
│ └── payments.csv # Example payment records
│
├── 📁 Diagrams
│ ├── ER_Schema_Initial.png # Initial ER diagram (without reviews table)
│ ├── ER_Schema_Updated.png # Updated ER diagram (with reviews table added)
│ └── Schema_Relationships.pdf # Annotated schema relationship chart
│
└── README.md
```

## 🧱 Database Design Summary  

#### **Core Entities**
- **Users & Roles:** For managing admins, staff, and customers.  
- **Customers & Suppliers:** For maintaining business relationships and logistics.  
- **Products & Categories:** For product classification and catalog organization.  
- **Warehouses & Inventory:** For stock tracking and movement across locations.  
- **Orders & Payments:** For managing order processing and financial transactions.  
- **Reviews:** Allows users to rate and comment on purchased products.


### ⚙️ Key Features  

- ✅ **Normalized relational schema (3NF)** to avoid redundancy  
- ✅ **Foreign key constraints** for maintaining data integrity  
- ✅ **Triggers** for automatic inventory updates upon order changes  
- ✅ **ENUM constraints** for predefined order and payment states  
- ✅ **Indexing** to improve query performance  
- ✅ **Many-to-many** product-supplier relationship table  
- ✅ **Timestamps & audit trails** for all key activities

### Diagrams
https://keep.google.com/u/0/media/v2/1ZJETwvUQMobAg9n6X8oFES40gFfrCr8WZjq3KEuSY9WKWy5ReVcj5gsY65y5owk/11AxosoqCK5Hw73XHr3xuFqrfk5VDsyOdmPc5wKZU-UHrNQJoIKtwdelkvfg0R9U?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp


