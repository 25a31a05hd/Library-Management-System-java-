# 📚 Library Management System Using Java

## 📌 Project Overview

The **Library Management System** is a Java-based desktop application developed to simplify and automate library operations. It helps librarians manage books, student records, book issuing, and returning activities efficiently.

The application uses **Java Swing** for the graphical user interface and **SQLite** for database management. It provides a simple dashboard to monitor library activities.

## 🎯 Objectives

- Manage book records digitally.
- Maintain registered student information.
- Simplify book issuing and returning.
- Track available and issued books.
- Reduce manual paperwork.
- Improve accuracy and efficiency in library management.

## ✨ Features

- **Dashboard:** Displays total books, registered students, issued books, and available books.
- **Book Management:** Add, view, update, delete, and search books.
- **Student Management:** Register, view, update, delete, and search students.
- **Issue Books:** Issue available books to registered students.
- **Return Books:** Update book return records and availability.
- **Search Functionality:** Quickly find books and student records.
- **Database Storage:** Stores information using SQLite.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java 17+ | Core programming language |
| Java Swing | Graphical user interface |
| JDBC | Database connectivity |
| SQLite | Database |
| Maven | Project build and dependency management |

## 📂 Project Structure

```text
LibraryManagementSystem/
│
├── pom.xml
├── README.md
├── .gitignore
│
└── src/
    └── main/
        └── java/
            └── com/
                └── example/
                    └── library/
                        └── LibraryApp.java
```

## ⚙️ Installation and Setup

### Prerequisites

Make sure you have installed:

- JDK 17 or above
- Apache Maven
- IntelliJ IDEA, Eclipse, or VS Code

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the Project

Open the downloaded project folder in your preferred Java IDE or terminal.

### Step 3: Build the Project

```bash
mvn clean compile
```

### Step 4: Run the Application

```bash
mvn clean compile exec:java
```

## 🖥️ Main Modules

1. Dashboard
2. Book Management
3. Student Management
4. Issue Book
5. Return Book
6. Search Records

## 🗄️ Database Tables

The application uses SQLite with the following tables:

- **Books:** Stores book ID, title, author, category, quantity, and available copies.
- **Students:** Stores student ID, name, email, and phone number.
- **Issues:** Stores issue ID, book ID, student ID, issue date, due date, return date, and status.

## 🚀 Future Enhancements

- Admin and librarian login system.
- Automatic fine calculation.
- Email and SMS notifications.
- Barcode and QR-code scanning.
- Online library management.
- Cloud database integration.
- Report generation.

## 🎓 Project Purpose

This project is developed as an academic and practical learning project to demonstrate Java programming, object-oriented programming, database connectivity, and graphical user interface development.

## 👩‍💻 Author

**Your Name**

B.Tech – Computer Science and Engineering

## 📄 License

This project is open-source and available for educational and learning purposes.
