# Restaurant Management System — PostgreSQL Database Project

A relational database project built after completing database fundamentals coursework.

## Goal
Design and implement a multi-location restaurant management database.

## Tech stack
- PostgreSQL
- SQL DDL / DML
- PL/pgSQL
- Views, indexes, constraints, roles

## What the database covers
- Locations and table management
- Menu, categories, ingredients, recipes
- Suppliers and purchase prices
- Inventory and low-stock monitoring
- Customers, orders, order items, feedback
- Staff, shifts, schedules, attendance
- Reservations

## Implemented
- Normalized relational schema
- Primary / foreign / unique / check constraints
- ENUM types for order and shift status
- Indexes for frequent lookup paths
- Views for operational reporting
- PL/pgSQL functions and procedure
- Role-based access model

## Example business questions answered
- Which ingredients are below minimum stock?
- What is the calculated total of an order?
- How many planned and actual hours did staff work?
- Which menu items are available and fast to prepare?