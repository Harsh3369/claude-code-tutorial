# Expense Tracker

A step-by-step tutorial project for building a personal expense tracking web app using Flask and SQLite.

## Overview

Users will be able to register, log in, and manage their personal expenses — adding, editing, and deleting records through a simple web interface. The project is structured as a guided tutorial where features are implemented incrementally across numbered steps.

## Tech Stack

- **Backend:** Python 3, Flask
- **Database:** SQLite
- **Frontend:** HTML/CSS/JavaScript (Jinja2 templates)
- **Testing:** pytest, pytest-flask

## Project Structure

```
expense-tracker/
├── app.py                  # Flask app and route definitions
├── database/
│   ├── __init__.py
│   └── db.py               # SQLite connection, table creation, seed data
├── templates/
│   ├── base.html           # Shared layout
│   ├── landing.html        # Home/landing page
│   ├── login.html          # Login page
│   └── register.html       # Registration page
├── static/
│   ├── css/style.css
│   └── js/main.js
├── requirements.txt
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.9+
- pip

### Setup

```bash
# Clone the repository
git clone https://github.com/Harsh3369/claude-code-tutorial.git
cd claude-code-tutorial

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python3 app.py
```

The app will be available at `http://localhost:5001`.

## Tutorial Steps

| Step | Feature |
|------|---------|
| 1 | Database setup (`get_db`, `init_db`, `seed_db`) |
| 2 | User registration |
| 3 | Login and logout |
| 4 | Profile page |
| 5 | List expenses |
| 6 | Expense dashboard |
| 7 | Add an expense |
| 8 | Edit an expense |
| 9 | Delete an expense |

## Running Tests

```bash
pytest
```
