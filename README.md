# Inventory-Management-System
# Build by using C# and Sql server

## Project Overview

Inventory Management System is a web-based application developed using ASP.NET Core MVC (.NET 8). The main objective of this system is to help organizations manage their inventory products and user records in an efficient and organized way.

The system allows administrators to perform essential inventory-related operations such as adding new products, updating product details, viewing inventory records, deleting products, managing users, authenticating login access, and generating inventory reports.

This application follows the Model-View-Controller (MVC) architectural pattern and is integrated with a SQL Server database using Entity Framework Core.

---

## Technologies Used

ASP.NET Core MVC (.NET 8)
SQL Server
Entity Framework Core
Bootstrap
HTML5 / CSS3
C#
Razor Pages

The project has been developed using Microsoft Visual Studio and Microsoft SQL Server Management Studio.

---

## Project Structure

InventoryMVC

Controllers

* HomeController.cs
* ProductsController.cs
* UsersController.cs
* AccountController.cs

Models

* Product.cs
* User.cs

Data

* InventoryDBContext.cs

Views

* Products
* Users
* Account
* Home

wwwroot

* css
* js
* bootstrap

appsettings.json

---

## Features

### User Authentication

The system includes a login mechanism that ensures only authorized users can access and manage inventory data.

### Product Management

Users can add new products, update existing product details, delete products, view the list of available products, and generate product-related reports.

### User Management

The system allows administrators to add new users, edit user information, delete users, and view user details when required.

---

## Database Configuration

Update the connection string in the appsettings.json file before running the application.

Example:

"ConnectionStrings": {
"DefaultConnection": "Server=YOUR_SERVER_NAME;Database=InventoryDB;Trusted_Connection=True;TrustServerCertificate=True;"
}

After updating the connection string, run the following command in the Package Manager Console to apply migrations:

Update-Database

---

## How to Run the Project

Step 1: Clone the repository
git clone https://github.com/your-username/InventoryMVC.git

Step 2: Open the project in Visual Studio

Step 3: Configure the SQL Server connection string in appsettings.json

Step 4: Run the database migration
Update-Database

Step 5: Press Ctrl + F5 to run the application

---

## Modules Included

Login Module
Product Management Module
User Management Module
Inventory Reporting Module

---

## Purpose of the Project

This project was developed to demonstrate the practical implementation of ASP.NET Core MVC architecture, CRUD operations, Entity Framework Core, SQL Server database integration, and user authentication in a real-world inventory management scenario.

---

## Author

Gotum Kumar
Software Engineering Student
SZABIST
