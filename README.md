# Task 1 – Library Management Database Design

## 📌 Description
This project sets up a relational database schema for a basic library system. It includes entities such as members, books, authors, and borrow records, allowing us to track which member has borrowed which book.

## 🧾 Tables
- **Member** – Library members
- **Author** – Book authors
- **Category** – Genres/categories of books
- **Book** – Book details
- **Borrow** – Records of books borrowed and returned

## 🔄 Relationships
- A Member can borrow many books
- A Book belongs to one Author and one Category
- A Borrow record links a Book and a Member

## 💾 Tools Used
- MySQL Workbench
- SQL (DDL statements)
