# Task-Notes Web Application

A clean, responsive task management web application built with Python and Flask. This project demonstrates full-stack development skills, including database management, routing, and modern styling with SCSS.

## 🚀 Features
- **Task Management:** Create, view, update, and delete tasks (CRUD functionality).
- **Responsive Design:** Fully optimized for mobile and desktop using custom SCSS.
- **Data Persistence:** Uses SQLAlchemy to manage a local database for storing notes.
- **Clean UI:** Simple and intuitive interface for distraction-free note-taking.

## 🛠️ Tech Stack
- **Backend:** Python, Flask, SQLAlchemy
- **Frontend:** HTML5, Jinja2, SCSS (Sass)
- **Environment:** Virtualenv, Pip

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd task-notes
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\(\Scripts\activate \%\%\)MAGIT_PARSER_PROTECT%%   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   python app.py
   ```
   The app will be available at `http://127.0.0`

## 📂 Project Structure
- `app.py`: Main application logic and routes.
- `static/`: Contains compiled CSS and design assets.
- `templates/`: HTML structures using Jinja2 templates.
- `instance/`: Local database storage.
