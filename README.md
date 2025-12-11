# DAT --- Developer & Alarm Tool

A productivity-focused web application built with **Python (Django)**
that combines a **Notes App**, multi-format **Tool Suite**, and upcoming
**reminder features with Google Calendar sync**.\
Designed to help developers perform quick conversions, store notes, and
manage their workflow --- all in one clean interface.

------------------------------------------------------------------------

## 🚀 Features

### 📝 Notes App

-   Create, edit, and delete notes effortlessly\
-   Clean UI for fast typing and retrieval\
-   Planned upgrade: **two‑way sync with Google Calendar** for reminders
    & due dates and other converters

------------------------------------------------------------------------

## 🧰 Tools Suite (17+ Converters)

A collection of useful developer-oriented tools including:

-   **Roman ↔️ Number Converter** (supports extended bars and
    validation)\
-   **Base Converters** (binary, octal, decimal, hex)\
-   **Date utilities**\
-   **String utilities**\
-   And many more developer-friendly mini-tools

Each tool is built with clean backend logic and user-friendly forms.

------------------------------------------------------------------------

## 🛠️ Tech Stack

### Backend

-   **Python (Django)**\
-   **PostgreSQL / SQLite**\
-   REST-style views for modularity

### Frontend

-   **HTML5, CSS3, JavaScript**\
-   Responsive, minimal UI\
-   Custom styles without heavy frameworks

### Deployment

-   Supports Render, Vercel (frontend static), Railway, etc.

------------------------------------------------------------------------

## ⚙️ Roman → Number Converter Logic (Highlight)

-   Handles 1--300000+ values including extended Roman numerals\
-   Custom validation to catch invalid repetitions (`VV`, `LL`, etc.)\
-   Reverse-traversal logic for accurate subtraction rules

------------------------------------------------------------------------

## 📂 Project Structure

    /dat
     ├── dat/
     ├── tools/
     │    ├── views.py
     │    ├── templates/
     │    └── utils/  (optional logic helpers)
     ├── notes/
     ├── templates/
     ├── static/
     └── requirements.txt

------------------------------------------------------------------------

## ✨ Key Highlights

-   Built with clean, readable Python code\
-   Modular tool architecture for easy addition of new converters\
-   Lightweight UI focused on real usability\
-   Error-handled views to prevent crashes\
-   Works smoothly on local and cloud-hosted PostgreSQL

------------------------------------------------------------------------

## 📌 Upcoming Features

-   Google Calendar **two-way sync** for reminders\
-   User authentication for personal notes\

------------------------------------------------------------------------

## Installation

Prerequisites
Make sure you have 'Python verasion 3.9 or more', 'pip', and 'Git' installed.

Clone the Repository in a new folder
 ```sh 
 git clone https://github.com/Infinity-3/DAT.git
```

Then create a virtual environent(venv) with this command
venv name can be anything; better name it related to project
 ```sh 
 python -m venv venv_name
```

Then activate the venv
```sh
venv_name\scripts\activate
```

Then change directory to the project and open VScode in that directory
```sh
cd DAT
code .
```

And install the required packages to run the project
```sh 
pip install -r requirements.txt
```

Start the Django development server by this command
```sh 
python manage.py runserver
```

Database Setup & Migrations
 Run the following commands to apply database migrations:
 ```sh
python manage.py migrate
 python manage.py createsuperuser  # Create admin user if required
```
------------------------------------------------------------------------

## 🤝 Contributions

Pull requests are welcome! Feel free to create issues for ideas or bugs.

------------------------------------------------------------------------

## 📜 License

MIT License --- free to use, modify, and share.