# AdonisPortfolio - Django Personal Portfolio Website

This is a **simple Django-based portfolio website** created by Adonis Jeswin. It demonstrates the basic use of templates, static files, views, and URL routing in Django.

---

## 🚀 Features

* Clean homepage with typing effect and black background
* Static file support for CSS and images
* Modular Django project structure
* Easy to expand with more pages

---

## 🛡️ Security Note (Safe for GitHub)

✅ This project is safe to upload to GitHub as long as you follow these:

* **DO NOT** commit `.env` files or sensitive secrets (not used in this version)
* **NO** database or user info included
* Uses only local static files (no API keys or credentials)

---

## 🗂️ Project Structure

```
AdonisPortfolio/
├── manage.py
├── AdonisPortfolio/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── portfolio/
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   └── portfolio/
│   │       └── home.html
│   └── static/
│       └── css/
│           └── style.css
└── db.sqlite3 (only created after running the project)
```

---

## ⚙️ Installation

```bash
# Clone the repository
https://github.com/yourusername/AdonisPortfolio.git
cd AdonisPortfolio

# (Optional) Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate

# Install Django
pip install django

# Run the server
python manage.py runserver

# Open in browser:
http://127.0.0.1:8000/
```

---

## 🧩 Customization

* Edit `home.html` in `portfolio/templates/portfolio/`
* Add your own CSS in `static/css/style.css`
* Add pages in `urls.py` and `views.py`

---

## 📸 Screenshot

> <img width="1793" height="903" alt="image" src="https://github.com/user-attachments/assets/387a519c-100e-443d-9818-8bc2b137c8bc" />


---

## 📄 License

This project is open-source and free to use under the MIT License.

