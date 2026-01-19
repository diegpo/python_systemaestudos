# 🐍 Python Study System

This project was developed using **Python** and **Django**, with the **exclusive purpose of study and learning**, exploring in practice the main concepts of the language and the framework.

This system serves as an **educational base**, where different features will be implemented incrementally, following good development practices.

---

## 🎯 Project Objective

The main goals of this project are:

- Consolidate knowledge in **Python**
- Learn and practice **Django in a hands-on way**
- Understand how the following work:
  - Authentication
  - Databases
  - Web project structure
  - Code organization
- Build a solid foundation for future projects

> ⚠️ **This project has no commercial purpose** and should not be used in production.  
> It exists solely as a **study and experimentation environment**.

---

## 🧠 Concepts Covered

### 🐍 Python
- Project structure
- Virtual environments
- Dependency management
- Organization best practices

### 🌐 Django
- Project and app creation
- URL routing system
- Views and Templates
- User authentication (login/logout)
- Route protection
- Django Admin
- SQLite database
- Environment variables

---

## 🗄️ Database

- Database used: **SQLite**
- Local database to simplify studies and testing
- Automatically managed by the Django ORM

---

## 🔐 Current Features

- ✅ Login system
- ✅ User authentication
- ✅ Protected dashboard
- ✅ Django Admin
- ✅ Secure configuration using `.env`
- ✅ Base structure ready for expansion

---

## 🚀 Technologies Used

- **Python 3**
- **Django**
- **SQLite**
- **HTML**
- **Git & GitHub**

---

## 📦 How to Run the Project Locally

```bash
# Clone the repository
git clone https://github.com/diegpo/python_systemaestudos.git

# Access the project folder
cd python_systemaestudos

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# Windows
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create a superuser
python manage.py createsuperuser

# Start the development server
python manage.py runserver
