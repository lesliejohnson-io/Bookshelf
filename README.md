# 📚 Bookshelf

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Flask](https://img.shields.io/badge/Flask-Web_App-black.svg)
![SQLite](https://img.shields.io/badge/Database-SQLite-lightgrey.svg)
![Status](https://img.shields.io/badge/Status-Active-green.svg)

## Overview

**Bookshelf** is a lightweight Python web application that allows users to manage a personal library directly from the browser.

The app serves HTML pages for creating, viewing, editing, and deleting books, while persisting data in a SQL database. All interactions happen through a clean browser-based UI backed by server-side Python logic.

---

## Features

- 📖 Add books via browser-based forms  
- ✏️ Edit book ratings  
- 🗑 Delete books from the library  
- 💾 Persistent storage using SQLite  
- 🔄 Full CRUD flow (Create, Read, Update, Delete)  

---

## Tech Stack

- **Python**
- **Flask**
- **HTML (Jinja templates)**
- **SQLite**

---

## Project Structure

```

Bookshelf/
├── instance/
│   └── books.db          # SQLite database
├── templates/
│   ├── index.html        # View all books
│   ├── add.html          # Add a new book
│   └── edit_rating.html  # Edit book rating
├── main.py               # Flask application logic
├── requirements.txt
└── README.md

````

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/lesliejohnson-io/Bookshelf.git
cd Bookshelf
````

---

### 2. Create and activate a virtual environment (recommended)

```bash
python -m venv .venv
```

**Windows**

```bash
.venv\Scripts\activate
```

**macOS / Linux**

```bash
source .venv/bin/activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Run the application

```bash
python main.py
```

---

### 5. Open in your browser

Navigate to:

```
http://127.0.0.1:5000
```

You can now add, edit, and delete books directly from the UI.

---

## Database

* Uses **SQLite** for simplicity and portability
* Database file is stored in the `instance/` directory
* No external database setup required

---

## Why This Project

This project demonstrates:

* Server-side Python web development
* Clean separation of concerns (routes, templates, persistence)
* SQL-backed data storage
* End-to-end browser → server → database flow

It’s designed to be simple, readable, and easy to extend.

---

## Possible Extensions

* Add author, genre, or notes fields
* Sort or filter books
* Add user authentication
* Deploy to a cloud platform (Render, Fly.io, Railway)

```
