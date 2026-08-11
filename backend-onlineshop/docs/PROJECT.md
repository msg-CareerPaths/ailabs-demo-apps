# Online Shop API

This project represents the backend of a small-scale e-commerce application, exposing a RESTful API built with Spring Boot.

## User Roles

The API supports two user roles:

- **Customer** - Standard user with shopping capabilities
- **Administrator** - User with management privileges

## API Features

### Customer Endpoints

- **Product Catalog**
  - Retrieve all products with essential details (name, price, description, etc.)
  - Retrieve detailed product information by ID
- **User Authentication**
  - Register a new account
  - Sign in and sign out (JWT-based)
- **Shopping Cart**
  - Cart management is handled client-side; the API exposes order creation
- **Order Management**
  - Place a new order
  - Retrieve own order history
  - Retrieve details of a specific order

### Administrator Endpoints

- Includes all customer endpoints
- **Product Management**
  - Create new products
  - Update existing product information
  - Delete products from the catalog
- **Order Administration**
  - Retrieve orders from all users
