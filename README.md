# Gym-Management-System
A WPF-based Gym Management System built with C#/.NET 7 and PostgreSQL for managing packages, clients, instructors, memberships, and payments.
# 🏋️ Gym Management System

A desktop-based **Gym Management System** developed using **C#, .NET 7, WPF, and PostgreSQL**. The application is designed to simplify and organize the major day-to-day operations of a gym through a centralized management system.

---

## 📌 Project Overview

The Gym Management System provides an easy-to-use platform for gym administrators to manage important gym activities such as **packages, clients, instructors, memberships, and payments**.

The system reduces manual record keeping and provides centralized storage of gym-related information. The dashboard also provides an overview of important gym statistics such as packages, memberships, and revenue.

---

## 🎯 Objectives

The main objectives of this project are:

- To computerize gym management activities.
- To maintain client information in a centralized database.
- To manage gym packages efficiently.
- To maintain instructor records.
- To manage memberships and payments.
- To reduce manual paperwork and data duplication.
- To provide quick access to gym records.
- To improve the overall efficiency of gym administration.

---

## 🚀 Features

### 📊 Dashboard
- Displays an overview of gym activities.
- Shows package and membership information.
- Provides revenue-related information.
- Helps administrators quickly understand the current status of the gym.

### 📦 Package Management
- Add gym packages.
- View available packages.
- Manage package duration.
- Manage package price.
- Manage package days.
- Add package images and descriptions.

### 👤 Client Management
- Add new clients.
- View client details.
- Manage client information.
- Store personal and contact details.
- Update and delete client records.

### 🧑‍🏫 Instructor Management
- Add instructor information.
- Store instructor personal details.
- Manage instructor salary.
- Store instructor title and contact information.
- Update and manage instructor records.

### 🪪 Membership Management
- Manage gym memberships.
- Associate memberships with clients and packages.
- Maintain membership-related information.
- Track membership status.

### 💳 Payment Management
- Maintain payment information.
- Store payment-related records.
- Help administrators manage gym transactions.

### ❓ FAQ
- Provides frequently asked questions and useful information for users.

### ℹ️ About
- Provides information about the application.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **C#** | Application development |
| **.NET 7** | Application framework |
| **WPF** | Desktop user interface |
| **PostgreSQL** | Database management |
| **Npgsql** | PostgreSQL connectivity |
| **XAML** | UI design |
| **Visual Studio Code** | Development environment |
| **Git & GitHub** | Version control and project hosting |

---

## 🏗️ Project Architecture

The project follows a structured architecture that separates different responsibilities of the application.

```text
Gym Management System
│
├── Assets
├── Components
├── Entities
├── Interfaces
├── Pages
├── Repositories
├── Resources
├── Security
├── ViewModels
├── Windows
│
├── MainWindow.xaml
└── Gym.Desktop.csproj
