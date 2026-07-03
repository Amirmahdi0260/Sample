# Blog Management System

A modern **Blog Management System** developed with **ASP.NET Core MVC** following the **Onion Architecture** principles. This project was built as a portfolio project to demonstrate clean architecture, authentication, validation, and database-driven web application development.

## 📖 Overview

The application allows administrators to create and manage blog posts while authenticated users can interact with published articles by leaving comments. The project focuses on maintainability, scalability, and clean separation of concerns.

## ✨ Features

- 🔐 Cookie-Based Authentication
- 👥 User Registration & Login
- 🛡️ Role-Based Authorization
- 📝 Create, Edit, Delete & Publish Articles
- 💬 Authenticated Users Can Post Comments
- 📄 Server-Side Pagination
- ✅ FluentValidation for Input Validation
- 🏗️ Onion Architecture
- 🗄️ Entity Framework Core
- 💾 SQL Server Database
- 📱 Responsive User Interface

## 🏛️ Architecture

The project is built using **Onion Architecture** to achieve a clean and maintainable codebase.

```
Presentation (ASP.NET Core MVC)
│
├── Application
│
├── Domain
│
└── Infrastructure
```

### Project Layers

- **Presentation** – MVC Controllers, Views, ViewModels
- **Application** – Business Logic, Services, DTOs
- **Domain** – Entities, Interfaces, Business Rules
- **Infrastructure** – EF Core, SQL Server, Repositories

## 🛠️ Technologies

- ASP.NET Core MVC
- C#
- Entity Framework Core
- SQL Server
- Cookie Authentication
- FluentValidation
- Bootstrap 5
- HTML5
- CSS3
- JavaScript

## 📂 Project Structure

```
BlogManagementSystem
│
├── Blog.Web
├── Blog.Application
├── Blog.Domain
└── Blog.Infrastructure
```

## 🚀 Getting Started

### Prerequisites

- .NET SDK
- SQL Server
- Visual Studio 2022

### Installation

```bash
git clone https://github.com/yourusername/BlogManagementSystem.git
```

```bash
cd BlogManagementSystem
```

Update the connection string in `appsettings.json`, then run:

```bash
dotnet ef database update
```

```bash
dotnet run
```

## 📸 Screenshots

> Add screenshots of:
>
> - Home Page
> - <img width="1200" height="900" alt="Image" src="https://github.com/user-attachments/assets/c706c800-75eb-4e51-86f7-c67f2c577df0" />

> - Blog Details
> - Login Page
> - Admin Dashboard
> - Create Article Page

## 🎯 Purpose

This project was developed as a portfolio application to demonstrate practical experience with:

- ASP.NET Core MVC
- Onion Architecture
- Cookie Authentication
- Entity Framework Core
- FluentValidation
- Repository Pattern
- Dependency Injection
- SQL Server
- Pagination
- Clean Code Principles

## 📄 License

This project is intended for educational and portfolio purposes.
