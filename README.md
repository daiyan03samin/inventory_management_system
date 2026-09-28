# Inventory Management System

## Overview
A Java‑based Inventory Management System demonstrating core software design patterns, clean architecture, and modular development. This project provides functionality for managing products, users, and system operations through an extensible and maintainable codebase. This system allows users to perform essential inventory operations such as adding, updating, and deleting products and managing users. The project emphasizes Object‑Oriented Programming (OOP) principles and implements multiple design patterns to ensure scalability and clean separation of concerns.

## Features
* Product Management: Create, update, delete, and view product details.

* Search & Filtering: Find products by ID, category, or name.

* User Management: Privileged users can manage other user accounts to maintain system integrity.

## Design Patterns Implemented

* Singleton — Ensures a single instance of the inventory manager

* Factory — Object creation for products or inventory items

* Strategy Pattern — Allows interchangeable algorithms for sorting/reporting

* MVC Architecture — Separates UI, logic, and data for maintainability

## Project Structure
* src/ — Main Java source code

* config/ — Database credentials and configurations

* models/ — Product, Supplier, InventoryItem classes

* controllers/ — Business logic and system operations

* apps/ — GUI components

* factories/ — Java factory design

* sessions/ — Maintain a session for the user

## Requirements
* Java 17+

* Maven

* IntelliJ or VS Code

* java -jar lib/mysql-connector-j-9.5.0.jar

## Contributors
Daiyan Abrar Samin — Database design, Models, Design Patterns

Mohamed Amine Hamidouch — System Architecture, Controllers, Views
