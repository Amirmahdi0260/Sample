<p align="center">
  <img src="images/logo.png" alt="Blog Management System Logo" width="180">
</p>

<h1 align="center">Blog Management System</h1>

<p align="center">
  A modern blog management system built with <b>ASP.NET Core MVC</b> following the <b>Onion Architecture</b> principles.
</p>

<p align="center">

![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-MVC-512BD4?style=for-the-badge&logo=.net)
![C#](https://img.shields.io/badge/C%23-Language-239120?style=for-the-badge&logo=c-sharp)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver)
![Entity Framework Core](https://img.shields.io/badge/EF_Core-ORM-6DB33F?style=for-the-badge)
![FluentValidation](https://img.shields.io/badge/FluentValidation-Validation-orange?style=for-the-badge)

</p>

---

# 📸 Preview

<p align="center">
  <img src="images/home.png" alt="Home Page">
</p>

---

# 📖 Overview

Blog Management System is a portfolio project developed with **ASP.NET Core MVC** using **Onion Architecture**.

The application allows administrators to create and manage blog articles while authenticated users can interact with published content by posting comments.

This project demonstrates modern software architecture, clean code principles, authentication, validation, and database-driven web application development.

---

# ✨ Features

- 🔐 Cookie-Based Authentication
- 👤 User Registration & Login
- 🛡️ Role-Based Authorization
- 📝 Create, Edit, Delete & Publish Articles
- 💬 Comment System (Authenticated Users Only)
- 📂 Category Management
- 📄 Server-Side Pagination
- ✅ FluentValidation
- 🏗️ Onion Architecture
- 💾 SQL Server Database
- ⚡ Entity Framework Core
- 🎨 Responsive User Interface

---

# 🏛️ Architecture

The project follows the **Onion Architecture** pattern to keep the application maintainable and scalable.

<p align="center">
  <img src="images/architecture.png" width="700">
</p>

### Project Layers

- **Presentation**
  - Controllers
  - Views
  - ViewModels

- **Application**
  - Services
  - DTOs
  - Business Logic

- **Domain**
  - Entities
  - Interfaces
  - Domain Rules

- **Infrastructure**
  - Entity Framework Core
  - SQL Server
  - Repositories
  - Authentication

---

# 📸 Application Screenshots

## 🏠 Home Page

<p align="center">
  <img src="images/home.png">
</p>

---

## 📄 Blog Details

<p align="center">
  <img src="images/post-details.png">
</p>

---

## 🔑 Login

<p align="center">
  <img src="images/login.png">
</p>

---

## 📝 Register

<p align="center">
  <img src="images/register.png">
</p>

---

## 💬 Comments

<p align="center">
  <img src="images/comments.png">
</p>

---

## ⚙️ Admin Dashboard

<p align="center">
  <img src="images/dashboard.png">
</p>

---

## ✍️ Create Article

<p align="center">
  <img src="images/create-post.png">
</p>

---

## 📂 Category Management

<p align="center">
  <img src="images/categories.png">
</p>

---

# 🛠️ Technologies

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

---

# 📂 Project Structure

```text
BlogManagementSystem
│
├── Blog.Web
├── Blog.Application
├── Blog.Domain
└── Blog.Infrastructure
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/YourUsername/BlogManagementSystem.git
```

## Navigate to Project

```bash
cd BlogManagementSystem
```

## Update Connection String

Open **appsettings.json** and configure your SQL Server connection string.

## Apply Migrations

```bash
dotnet ef database update
```

## Run Application

```bash
dotnet run
```

---

# 💡 Skills Demonstrated

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

---

# 📌 Future Improvements

- Image Upload
- Search Functionality
- Tags
- Rich Text Editor
- User Profile
- REST API
- Docker Support
- Unit Testing
- Logging (Serilog)

---

# 📄 License

This project was created for educational and portfolio purposes.
