Here’s a structured **README.md** draft for your project:  

***

# 📘 ASP.NET Core Minimal API - CRUD Example  

This project is a simple demonstration of an **ASP.NET Core Minimal API** that performs basic **CRUD (Create, Read, Update, Delete)** operations.  
It also integrates **built-in middlewares** such as **URL Rewriter**, along with a **custom middleware** to showcase extensibility and request handling in ASP.NET Core.  

***

## ✨ Features  
- ✅ ASP.NET Core Minimal API (lightweight API definition)  
- ✅ CRUD operations (Create | Read | Update | Delete)  
- ✅ Uses in-memory data storage (for demo purposes)  
- ✅ Built-in middleware: **URL Rewriter** to handle request redirection  
- ✅ Custom middleware: demonstrates request/response handling logic  
- ✅ Lightweight and beginner-friendly project structure  

***

## 🛠️ Prerequisites  
- [.NET 6.0 SDK](https://dotnet.microsoft.com/download/dotnet/6.0) or later  
- IDE such as **Visual Studio 2022** or **Visual Studio Code**  

***

## 🚀 Getting Started  

### 1. Clone the repository  
```bash
git clone https://github.com/your-username/minimal-api-crud.git
cd minimal-api-crud
```

### 2. Restore dependencies  
```bash
dotnet restore
```

### 3. Run the application  
```bash
dotnet run
```

The API will be available at:  
```
https://localhost:5001
http://localhost:5000
```

***

## 📡 API Endpoints  

**Base URL:** `/api/items`  

| Method | Endpoint         | Description             |
|--------|-----------------|-------------------------|
| GET    | `/api/items`     | Get all items           |
| GET    | `/api/items/{id}` | Get item by ID          |
| POST   | `/api/items`     | Create a new item       |
| PUT    | `/api/items/{id}` | Update an existing item |
| DELETE | `/api/items/{id}` | Delete an item          |

***

## ⚙️ Middlewares  

### 🔹 Built-In Middleware (URL Rewriter)  
- Redirects specific routes (e.g., `/old-route` → `/new-route`).  
- Configured using `RewriteOptions`.  

### 🔹 Custom Middleware  
- Example middleware logs request execution time and path.  
- Demonstrates how to create and use your own middleware component in the request pipeline.  

***
