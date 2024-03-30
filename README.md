# E-commerce Product Management System - Spring Data REST API

## Project Overview
This project is an implementation of a RESTful API for managing products in an e-commerce platform using Spring Data REST. It is designed to provide a simple and efficient way to handle CRUD operations on product entities within an e-commerce database.

## Features
- **RESTful API Endpoints**: CRUD operations for products, allowing for the creation, retrieval, updating, and deletion of product records.
- **Database Integration**: Utilizes a MySQL database to store product information.
- **Spring Data REST**: Simplifies the development of hypermedia-driven REST web services on top of Spring Data repositories.

## Java and Spring Features
- **Spring Boot**: Provides a robust and flexible framework for developing Java-based applications with minimal configuration.
- **Spring Data JPA**: Facilitates the implementation of JPA-based repository layers.
- **Spring Data REST**: Automatically exposes Spring Data JPA repositories as hypermedia-driven RESTful services.
- **Java Persistence API (JPA)**: Offers a specification for object-relational mapping to manage relational data in Java applications.
- **MySQL Database**: Utilizes a MySQL database for storing product information.

## API Endpoints
- `GET /products`: Retrieve all products.
- `GET /products/{id}`: Retrieve a product by its ID.
- `POST /products`: Add a new product.
- `PUT /products/{id}`: Update an existing product.
- `DELETE /products/{id}`: Delete a product by ID.

## Getting Started
- Clone the repository.
- Configure the database connection in `application.properties`.
- Run `ProductSpringDataRestRepositoryApplication` to start the application.
- Use a tool like Postman to test the API endpoints.

## Author
Created by Michal Frost.

Happy coding!