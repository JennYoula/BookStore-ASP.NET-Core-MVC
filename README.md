# BookStore-ASP.NET-Core-MVC
"ASP.NET Core MVC BookStore project with CRUD operations, developed by Jennifer YOULA as part of Prof. Marcel Stefan Wagner’s course."

# 📚 BookStore - ASP.NET Core MVC Project

## 👩‍💻 Author
- **Jennifer YOULA**

## 👨‍🏫 Professor
- **Prof. Marcel Stefan Wagner, PhD**

## 📖 Project Overview
BookStore is an ASP.NET Core MVC application that simulates a simple online bookstore.
It demonstrates the use of **C#**, **Razor Views**, **TagHelpers**, **Bootswatch** for styling, and
the implementation of CRUD operations in-memory without a database.

## 🛠️ Features
- List all books with search functionality
- Create, edit, and delete books
- View detailed information about each book
- Validation for form inputs (title, author, price, etc.)
- Custom TagHelper for confirmation modals
- Responsive layout using Bootstrap / Bootswatch theme

## 📂 Project Structure
- **Models/** → Book, Genre  
- **Controllers/** → BooksController with CRUD logic  
- **Services/** → InMemoryBookService (in-memory repository)  
- **Views/** → Razor views for Index, Create, Edit, Details, Delete  
- **TagHelpers/** → Custom confirmation modal  
- **wwwroot/** → CSS, JS, screenshots  

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/JennYoula/BookStore-ASP.NET-Core-MVC.git
