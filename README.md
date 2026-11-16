# GameStore — Full-Stack .NET & React CRUD Application

A full-stack video game catalog management application built to practice **ASP.NET Core Minimal APIs**, **Entity Framework Core**, and **React with TypeScript**.

## Tech Stack

**Backend (`GameStore.Api`)**
* .NET 10 / ASP.NET Core Minimal APIs
* Entity Framework Core 10 (Code-First Migrations & Automatic Seeding)
* SQLite
* DTOs & Data Annotations validation

**Frontend (`GameStore.React`)**
* React & TypeScript
* Vite
* React Router
* Bootstrap

## Features

* **Full CRUD for Games:** View all games, add new games, edit existing entries, and delete games with a confirmation modal.
* **Relational Data & Seeding:** Links games to genres (`Fighting`, `RPG`, `Platformer`, `Racing`, `Sports`) and automatically seeds genres and applies EF Core migrations on startup.
* **Clean API Architecture:** Separates database entities (`Models`) from request/response contracts (`Dtos`) and groups routes using Minimal API endpoint extensions.


Prerequisites
.NET 10 SDK

Node.js (v18+ recommended)

1. Run the Backend API
Bash
cd GameStore.Api
dotnet run
The API will start, create GameStore.db, apply migrations, and seed default genres automatically.

2. Run the Frontend App
Bash
cd GameStore.React
npm install
npm run dev