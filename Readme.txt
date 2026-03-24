Product Catalog API (.NET 8)

Project Overview:
This project implements a basic ASP.NET Core Web API to manage product catalog details.
It provides APIs to retrieve product information and associated product attributes.

Download and unzip the folder.

Technologies Used:

 .NET 8 Web API
 Entity Framework Core
 SQL Server
 Swagger UI

Steps to Run:

1. Open solution in Visual Studio 2022
2. Update connection string in appsettings.json
3. Open Package Manager Console
4. Run:
   Add-Migration InitialCreate
   Update-Database
5. Run the project

API Endpoints:

1. GET /api/products/{id}
   Returns single product details

2. GET /api/products
   Returns all products sorted by AverageCustomerRating (Descending)

3. GET /api/products/{id}/attributes
   Returns attributes of a given product

Notes:

Entity Framework Code-First approach used
Basic exception handling implemented
Sample data seeded at application startup
Swagger enabled for API testing
