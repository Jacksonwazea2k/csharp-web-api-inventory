# C# ASP.NET Core RESTful Inventory API

A modern RESTful Web API built with C# and ASP.NET Core 8, utilizing Entity Framework Core and SQLite for lightweight local persistence. This project demonstrates enterprise backend architecture, full CRUD operations, database migrations, and OpenAPI (Swagger) documentation.

## 🚀 Tech Stack

* **Framework:** .NET 8.0 / ASP.NET Core Web API
* **Database:** SQLite
* **ORM:** Entity Framework Core 8.0
* **Documentation:** Swagger UI / OpenAPI

## 🛠️ Features

* Full CRUD functionality for inventory management (`GET`, `POST`, `PUT`, `DELETE`).
* Asynchronous database operations using EF Core (`ToListAsync`, `FindAsync`, `SaveChangesAsync`).
* Automated primary key indexing and model attributes.
* SQLite local database file generation via EF Core Migrations.
* Interactive API testing interface via Swagger UI.

## 📌 API Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| **GET** | `/api/Items` | Retrieve all inventory items |
| **GET** | `/api/Items/{id}` | Retrieve a single inventory item by ID |
| **POST** | `/api/Items` | Create a new inventory item |
| **PUT** | `/api/Items/{id}` | Update an existing inventory item |
| **DELETE** | `/api/Items/{id}` | Delete an inventory item |

## ⚙️ Getting Started

### Prerequisites
* [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
* Visual Studio 2022

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Jacksonwazazk/csharp-web-api-inventory.git](https://github.com/Jacksonwazazk/csharp-web-api-inventory.git)
   cd csharp-web-api-inventory