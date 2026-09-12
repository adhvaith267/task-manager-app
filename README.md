<div align="center">

# Task Manager

A full-featured task management web application built with Python, Flask, and SQLite.

[![Python](https://img.shields.io/badge/Python-3.6%2B-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.x-black.svg)](https://flask.palletsprojects.com/)
[![SQLite](https://img.shields.io/badge/Database-SQLite-07405e.svg)](https://www.sqlite.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Issues](https://img.shields.io/github/issues/adhvaith267/task-manager-app)](https://github.com/adhvaith267/task-manager-app/issues)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Overview

Task Manager is a lightweight, self-hosted web application for organizing and tracking daily tasks. It provides complete CRUD functionality, status-based filtering, due date tracking, and a real-time statistics dashboard, all wrapped in a clean, responsive interface.

## Features

- **Full CRUD Operations** — Create, read, update, and delete tasks seamlessly
- **Status Filtering** — Filter tasks by All, Pending, In Progress, or Completed
- **Due Date Management** — Assign and track deadlines for each task
- **Statistics Dashboard** — Real-time overview of task counts and progress
- **Modern UI** — Clean design with smooth hover animations
- **Responsive Design** — Fully optimized for desktop, tablet, and mobile devices

## Tech Stack

| Layer      | Technology               |
|------------|---------------------------|
| Backend    | Python, Flask             |
| Database   | SQLite                    |
| Frontend   | HTML5, CSS3, JavaScript   |

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.6 or higher
- pip (Python package manager)
- A modern web browser

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/adhvaith267/task-manager-app.git
cd task-manager-app
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install flask
```

### 4. Run the application

```bash
python app.py
```

The application will be available at `http://localhost:5000`.

## Usage

1. Navigate to `http://localhost:5000` in your browser.
2. Add a new task using the input form.
3. Set a status and due date for each task.
4. Use the filter tabs to view tasks by status.
5. Track overall progress via the statistics dashboard.

## Project Structure

```
task/
├── static/
│   ├── custom.css       # Application styles
│   └── custom.js        # Client-side scripts
├── templates/
│   ├── base.html        # Base layout template
│   ├── index.html       # Main task list view
│   └── task_form.html   # Add/edit task form
├── app.py               # Application entry point
├── database.db          # SQLite database
└── README.md            # Project documentation
```
