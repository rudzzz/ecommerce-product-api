<h1>E-Commerce Product API</h1> 

## Project description

<p align="justify">
This project is an API for managing products and categories in an e-commerce application. It provides a robust backend solution for handling product-related operations, including creating, retrieving, updating, and deleting products. 
    
The API utilizes C# programming language  along with ASP.NET Core framework, offering a scalable and efficient platform for building modern web applications. The project also incorporates Entity Framework Core, a powerful Object-Relational Mapping (ORM) tool, to interact with        the underlying database. 
    
With the help of an in-memory database, the API ensures seamless data persistence during development and testing phases. Additionally, the integration of Swagger/OpenAPI enables easy documentation and exploration of the API endpoints, facilitating efficient API consumption and       integration.
</p>

## API Endpoints

<p align="justify">
    The API exposes the following endpoints:

    GET /api/products: Retrieves all products.
    GET /api/products/{id}: Retrieves a specific product by ID.
    POST /api/products: Creates a new product.
    PUT /api/products/{id}: Updates an existing product.
    DELETE /api/products/{id}: Deletes a product.
    POST /api/products/Delete: Deletes multiple products by providing a list of product IDs as a query parameter.

For detailed information on each endpoint, you can explore the API documentation using Swagger. When running the application in the development environment, Swagger UI can be accessed at /swagger/index.html.
</p>

## Database Configuration

<p align="justify">
By default, the project uses an in-memory database named "Shop" for simplicity and ease of testing. However, you can easily switch to a different database provider.
</p>

## Technologies used :books:

- [C#]
- [ASP.NET Core]
- [In-Memory Database]
- [Swagger/OpenAPI]

Copyright :copyright: 2023 - E-Commerce Product API
