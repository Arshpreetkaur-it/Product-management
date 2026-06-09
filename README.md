# Product Management System (REST API)

This is a Spring Boot REST API assignment for managing products, built using a clean layered architecture and MySQL database integration.

## 🛠️ Tech Stack
- *Backend:* Spring Boot v3.x, Spring Data JPA
- *Database:* MySQL
- *Testing Tool:* Postman
- *Build Tool:* Maven

## 📁 Project Architecture
The project follows a standard *Layered Architecture*:
- *Model (Product.java):* Represents the database entity.
- *Repository (ProductRepository.java):* Handles database operations using JpaRepository.
- *Service (ProductService.java):* Contains business logic.
- *Controller (ProductController.java):* Exposes REST API endpoints.

## 🚀 API Endpoints Tested
- POST /api/products - Create/Add a new product
- GET /api/products - Get all products
- GET /api/products/{id} - Get a specific product by ID
- PUT /api/products/{id} - Update product details
- DELETE /api/products/{id} - Delete a product

## 🔧 Database Setup
1. Open MySQL Client or Workbench.
2. Run the following command to create the database:
   ```sql
   CREATE DATABASE product_db;# Product Management System (REST API)

This is a Spring Boot REST API assignment for managing products, built using a clean layered architecture and MySQL database integration.

## 🛠️ Tech Stack
- *Backend:* Spring Boot v3.x, Spring Data JPA
- *Database:* MySQL
- *Testing Tool:* Postman
- *Build Tool:* Maven

## 📁 Project Architecture
The project follows a standard *Layered Architecture*:
- *Model (Product.java):* Represents the database entity.
- *Repository (ProductRepository.java):* Handles database operations using JpaRepository.
- *Service (ProductService.java):* Contains business logic.
- *Controller (ProductController.java):* Exposes REST API endpoints.

## 🚀 API Endpoints Tested
- POST /api/products - Create/Add a new product
- GET /api/products - Get all products
- GET /api/products/{id} - Get a specific product by ID
- PUT /api/products/{id} - Update product details
- DELETE /api/products/{id} - Delete a product

## 🔧 Database Setup
1. Open MySQL Client or Workbench.
2. Run the following command to create the database:
   ```sql
   CREATE DATABASE product_db;
