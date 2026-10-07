# Retail Inventory Management System

A Java-based **Retail Inventory Management System** designed for small retail businesses to manage products, stock, suppliers, orders, users, and reports efficiently.

This project is being developed as part of a **Junior Java Developer Internship**. The current Week 1 work focuses on **project planning, requirement analysis, architecture design, design patterns, database planning, and Java code scaffolding**.

## Project Objective

The objective of this project is to design a structured inventory management solution that can:

- Manage products and categories
- Track available stock
- Manage suppliers
- Process customer orders
- Update inventory automatically
- Detect low-stock products
- Manage users and authentication
- Generate inventory and sales reports

## Technology Stack

- **Language:** Java
- **Database:** MySQL
- **Database Connectivity:** JDBC
- **Build Tool:** Maven
- **Version Control:** Git & GitHub

## System Architecture

The project follows a **Layered Architecture**:

```text
User Interface
      ↓
Controller Layer
      ↓
Service Layer
      ↓
DAO Layer
      ↓
MySQL Database
```

This architecture separates user interaction, business logic, and database operations, making the application easier to maintain, test, and extend.

## Main Modules

### 1. Product Management
Handles adding, updating, deleting, searching, and viewing products.

### 2. Inventory Management
Tracks product quantities, stock updates, and minimum-stock levels.

### 3. Order Management
Handles customer orders, verifies stock availability, calculates order totals, and updates inventory.

### 4. Supplier Management
Stores and manages supplier details and their associated products.

### 5. User Management
Handles authentication and user roles.

### 6. Reporting
Provides inventory, sales, purchase, and low-stock reports.

## Design Patterns

The proposed system uses the following design patterns:

- **MVC (Model-View-Controller)** — separates application data, interface, and control logic.
- **DAO (Data Access Object)** — separates database operations from business logic.
- **Singleton** — provides centralized database connection management.
- **Factory** — supports creation of different report types.

## Project Structure

```text
src/main/java/com/inventory/
│
├── controller/
├── model/
├── service/
├── dao/
├── factory/
└── util/

database/
└── schema.sql

pom.xml
README.md
```

## Database

The proposed MySQL database includes:

- Users
- Products
- Categories
- Suppliers
- Inventory
- Customers
- Orders
- Order Items

## Current Status

### Week 1 — Project Planning & Architecture Design

Completed:

- Requirements analysis
- High-level architecture design
- Module planning
- Database design
- Design pattern selection
- Java package structure
- Pseudocode
- Initial Java code scaffolding

> **Note:** The project is currently in the planning and initial development stage. Full functionality will be implemented progressively in upcoming phases.

## Future Enhancements

Future versions may include:

- Complete JDBC integration
- User authentication
- Barcode scanning
- Automated low-stock alerts
- Dashboard and analytics
- REST API
- Improved graphical interface
- Cloud deployment

## Author

**Krishna**

Junior Java Developer Internship Project
