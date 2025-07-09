# 📚 Library Management System - Spring Boot Web Application

### Author: Efe Saka
### University Project – 2025
### Technology Stack: Java, Spring Boot, Thymeleaf, H2, Maven

---

## 🔍 Project Overview

The Library Management System is a Java-based full-stack web application developed using the Spring Boot framework. The main goal of this project is to allow users to manage a collection of books, supporting operations such as adding, editing, deleting, and viewing book details.

The application is lightweight, fast, and self-contained — it uses an H2 in-memory database, meaning no manual database setup is required. It runs directly from IntelliJ IDEA with minimal configuration.

---

## 🎯 Features

- Add new books with title, author, description, and page count
- Edit or delete existing books
- View full details of each book
- Auto-loading SQL scripts (schema and sample data)
- MVC architecture for clean separation of concerns
- Responsive and user-friendly interface with Thymeleaf
- Google Translate support for multi-language accessibility (English, Turkish, Polish)
- Fully self-contained (no MySQL or external DB required)

---

## 🛠️ Technologies Used and Why

| Technology       | Reason for Use |
|------------------|----------------|
| **Java 17**       | Primary programming language |
| **Spring Boot**   | Simplifies backend development and auto-configures most of the boilerplate code |
| **Spring MVC**    | Provides structured routing and controller logic |
| **Spring Data JPA** | For easy database communication using Java objects |
| **Thymeleaf**     | Powerful templating engine for rendering dynamic HTML views |
| **H2 Database**   | Lightweight, in-memory database ideal for testing and academic projects — no need for manual setup |
| **Maven**         | Manages dependencies and builds the project cleanly |
| **IntelliJ IDEA** | Chosen IDE for development, supports Spring Boot and Maven very well |
| **Google Translate Widget** | Adds multilingual support and accessibility for a wider audience |

---

## ⚙️ Application Structure (MVC)

- `Book.java` – Model class representing the book entity
- `BookRepository.java` – Interface for database operations
- `BookService.java` – Business logic for managing books
- `BookController.java` – Web routes and request handling
- `index.html`, `new_book.html`, `edit_book.html`, `book_details.html` – Thymeleaf templates for frontend views

---

## 🔧 Setup Instructions

### ✅ Prerequisites
- Java JDK 17 or higher
- Maven installed
- IntelliJ IDEA

### 🚀 Steps to Run the Application

1. **Open the project in IntelliJ IDEA**
2. Maven will automatically download the required dependencies
3. No SQL configuration is needed – `schema.sql` and `data.sql` will auto-execute
4. Run the application by right-clicking on `LibraryManagementApplication.java` → Run
5. Open your browser and go to:
   **http://localhost:8080**

---

## 📡 API Endpoints Summary

| Method | URL                  | Description           |
|--------|----------------------|------------------------|
| GET    | `/books`             | View all books         |
| GET    | `/books/new`         | Add new book form      |
| POST   | `/books`             | Save new book          |
| GET    | `/books/edit/{id}`   | Edit book form         |
| POST   | `/books/edit/{id}`   | Update book data       |
| POST   | `/books/delete/{id}` | Delete book            |
| GET    | `/books/{id}`        | View book details      |

---

## 🧑‍💻 How to Use the Application

- The homepage lists all books.
- Click “Add New Book” to open the form and submit a new book.
- Click on a book title or “Details” to view its information.
- Use “Edit” and “Delete” buttons to update or remove books.
- Clicking the “Library” title redirects you to the homepage from any page.
- After any action, users are automatically redirected to the main list.
- Google Translate allows switching the website language (English, Turkish, Polish).

---

## 🌱 Future Improvements (Optional)

- Add user authentication (admin vs normal user)
- Allow image upload for book covers
- Implement search and category filtering
- Add export options (CSV, PDF)
- Improve responsive design and mobile experience

---

## 📬 Contact

Name:Efe Saka
My ID: 55934
