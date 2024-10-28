# eShop Web Application 
- eShop Web Application With T3H INSTITUTE OF INFORMATION TECHNOLOGY
## Overview
This project is a fully functional **eShop** web application built using **ASP.NET Core** and **SQL Server**. It demonstrates the typical functionalities of an e-commerce system, including product catalog management, shopping cart, user authentication, order processing, and more. 

The application is structured following ** ... Architecture**, providing a well-organized, maintainable, and scalable codebase. The back-end leverages ASP.NET Core's MVC pattern for the UI and Web API services, while **Entity Framework Core** is used for database interactions.

## Features
- **User Authentication**: Register, Login, Logout, and Role-based access control.
- **Product Management**: Admin functionalities for adding, updating, and deleting products.
- **Shopping Cart**: Add to cart, update quantities, and remove items.
- **Order Processing**: Place orders, view order history, and manage order statuses.
- **Payment Gateway**: Integration with a mock payment service.
- **SQL Server Integration**: Database management using SQL Server.

## Technologies Used
- **ASP.NET Core 8.0**
- **Entity Framework Core 8**
- **SQL Server 2022**
- **Bootstrap 5** for responsive UI design
- **Identity** for user authentication and role management
- **AutoMapper** for mapping between data and view models
- **Dependency Injection** for better decoupling
- **LINQ** for querying the database
###
## Prerequisites
Before running the project, make sure you have the following installed:
- .NET SDK 8.0+
- SQL Server 2022+
- Visual Studio 2022 (or any IDE that supports .NET Core)
- Entity Framework Core tools

## Installation

### 1. Clone the repository

>>  bash

		git clone https://github.com/yourusername/eshop.git
		cd eshop

### 2. Configure the database

Open appsettings.json in the root of the project.
Replace the ConnectionStrings section with your own SQL Server connection details:

>>
	"ConnectionStrings": {
	"DefaultConnection": "Server=YOUR_SERVER_NAME;Database=eShopDb;Trusted_Connection=True;MultipleActiveResultSets=true"
	}


### 3. Apply database migrations

Run the following commands to apply the database migrations and create the database:

>>
	dotnet ef database update


# Contact
For any issues or inquiries, feel free to contact me at [email@example.com].
		