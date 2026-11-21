# Bank Management System

A console-based Bank Management System developed in C++ using Object-Oriented Programming (OOP). The project provides a range of banking operations, client and user management, transaction tracking, and currency exchange functionalities.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [OOP Concepts](#oop-concepts)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Data Storage](#data-storage)
- [How to Run](#how-to-run)
- [Learning Outcomes](#learning-outcomes)

## Overview

The Bank Management System is designed to simulate essential banking operations through an interactive console interface.

It allows users to manage bank clients, perform financial transactions, control user access permissions, review transaction records, and manage currency exchange operations.

The project focuses on applying OOP principles to build a modular and organized application, with responsibilities separated across different classes and header files.

## Features

### 1. Client Management
- Display all registered clients.
- Add new clients.
- Update client information.
- Delete existing clients.
- Search for clients using their account numbers.

### 2. Banking Transactions
- **Deposit:** Add money to a client's account.
- **Withdraw:** Withdraw money while checking the available balance.
- **Transfer:** Transfer money between client accounts.
- **Total Balances:** Display the total balance of all clients.
- **Transfer Log:** View transaction records, including dates, account numbers, transferred amounts, and balances after transfers.

### 3. User Management
- Display all registered users.
- Add new users.
- Update user information.
- Delete users.
- Search for users.
- Assign access permissions to users.

### 4. Authentication & Access Control
- User login and logout.
- Login register to track login activities.
- Permission-based access control.
- Restrict access to specific operations based on user permissions.

### 5. Currency Exchange
- Display the available currencies.
- Search for currencies by country or currency code.
- Update currency exchange rates.
- Convert amounts between different currencies using stored exchange rates.

## OOP Concepts

The project applies several Object-Oriented Programming concepts:

- **Classes & Objects:** Organizing the application into classes, each responsible for specific functionality.
- **Encapsulation:** Keeping data members private and providing controlled access through public methods and properties.
- **Inheritance:** Reusing common functionality through base classes such as `clsPerson` and `clsScreen`.
- **Constructors:** Initializing objects and setting their initial states.
- **Getters & Setters:** Controlling access to private data members.
- **Static Members & Methods:** Implementing shared functionality and class-level operations.
- **Access Specifiers:** Controlling the visibility and accessibility of class members.

## Project Structure

The project is organized into separate header files, with each class handling a specific responsibility.

| File / Class | Responsibility |
|---|---|
| `clsPerson` | Base class for personal information |
| `clsBankClient` | Client data and banking operations |
| `clsUser` | User data, authentication, and permissions |
| `clsCurrency` | Currency information and conversion |
| `clsScreen` | Shared screen functionality and access control |
| `clsMainScreen` | Main application menu |
| `clsTransactionsScreen` | Transactions menu |
| `clsManageUsersScreen` | User management menu |
| `clsCurrencyExchangeMainScreen` | Currency exchange menu |
| `clsDate` | Date-related operations |
| `clsString` | String manipulation utilities |
| `clsInputValidate` | Input validation |
| `clsUtil` | General utility functions |

The project also contains separate screen classes for individual operations, such as adding, updating, deleting, finding, and listing clients and users.

## Technologies Used

- **Programming Language:** C++
- **Programming Paradigm:** Object-Oriented Programming (OOP)
- **File Handling:** C++ File Streams (`fstream`)
- **Data Structures:** `vector`, `string`
- **Development Environment:** Microsoft Visual Studio

## Data Storage

The application uses text files to store and retrieve information, including:

- `Clients.txt` – Client records.
- `Users.txt` – User records.
- `Currencies.txt` – Currency information and exchange rates.
- `TransferLog.txt` – Transfer transaction records.
- `LoginRegester.txt` – Login activity records.

This allows application data to persist between program executions.

## How to Run

1. Clone or download the repository.
2. Open the `.sln` or `.vcxproj` project in Microsoft Visual Studio.
3. Build the project.
4. Run the application.
5. Log in using an existing user account from the provided `Users.txt` file.

**Note:** Keep the provided text files in the application's working directory so the application can access its stored data.

## Learning Outcomes

Through this project, I practiced applying OOP principles in a larger C++ application, organizing code into reusable classes, working with file handling, implementing authentication and access control, and managing data through different interconnected components.


