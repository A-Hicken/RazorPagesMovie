🎬 Razor Pages Movie App

ASP.NET Core Razor Pages application built with C# and Entity Framework Core using SQLite.

This project demonstrates full CRUD functionality, server-side filtering, EF Core migrations, and clean Razor Pages architecture.

✨ Features

Create, Read, Update, Delete (CRUD) operations

Server-side filtering by title and genre

SQLite database integration

Entity Framework Core migrations

Custom date formatting (dd/MM/yyyy)

Model binding and validation

Razor Pages structure with separation of concerns

🛠 Tech Stack

.NET 8

ASP.NET Core Razor Pages

C#

Entity Framework Core

SQLite

.NET CLI

Git

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/A-Hicken/RazorPagesMovie.git
cd RazorPagesMovie

2️⃣ Restore Dependencies
dotnet restore

3️⃣ Apply Database Migrations
dotnet ef database update


If migrations do not exist, create them:

dotnet ef migrations add InitialCreate
dotnet ef database update

4️⃣ Run the Application
dotnet watch


Then open:

https://localhost:xxxx


Navigate to /Movies to view the application.

📂 Project Structure
Models/
Pages/
Migrations/
Program.cs
appsettings.json


Models/ – Application data models

Pages/ – Razor Pages (UI + logic)

Migrations/ – EF Core database migrations

Program.cs – Application configuration and service registration

🧠 What I Practiced

Configuring EF Core with SQLite

Managing migrations and database updates

Implementing filtering logic

Debugging SDK/runtime version conflicts

Structuring Razor Pages for maintainability

Handling merge conflicts and Git workflows

📌 Notes

This project was extended beyond the base tutorial to include:

Custom date formatting

Filtering functionality

Cleaned migration configuration

Updated .NET 8 compatibility

💜 Author

Amberlie Hicken
Frontend & Full-Stack Developer
