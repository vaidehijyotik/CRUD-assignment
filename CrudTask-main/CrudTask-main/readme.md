# Task Manager

A web-based task management application built with Flask and SQLAlchemy.  
The app provides a clean interface to manage tasks with basic create, update, and tracking features.

---

## Overview

This project demonstrates a simple CRUD workflow using Flask.  
Tasks can be added, edited, marked as completed, and removed.  
Data is stored locally using SQLite.

---

## Features

- Create new tasks  
- Edit existing tasks  
- Mark tasks as completed  
- Delete tasks  
- Clean and minimal interface  
- Persistent storage with SQLite  

---

## Tech Stack

- **Backend:** Python, Flask  
- **Database:** SQLite, SQLAlchemy  
- **Frontend:** HTML, CSS  

---

## Project Structure

crudtask/
│── app.py
│
├── templates/
│ ├── index.html
│ ├── add.html
│ └── edit.html
│
└── static/
└── style.css


---

## Getting Started

### Prerequisites

- Python 3.9 or higher  
- pip package manager  

---

### Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/task-manager.git
cd task-manager

2. Install dependencies
pip install flask flask-sqlalchemy

3. Run the application
python app.py


Access the App

Open your browser and visit:
http://127.0.0.1:5000



Usage

Use Add task to create a new entry
Select Edit to update task details
Click Done to mark a task as completed
Use Delete to remove a task



Database

SQLite database (tasks.db)
Automatically created on first run
No manual configuration required


Author
Sujal Ostwal