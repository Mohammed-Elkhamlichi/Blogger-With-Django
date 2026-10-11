# 📝 Blogger — Django Blog Application

A blog web application built with **Python and Django**, designed to provide a platform for publishing, managing, and reading blog posts.

## 📌 Overview

Blogger is a web development project that demonstrates how to build a blog platform using Django, including server-side application logic, database integration, and dynamic web pages.

🔗 **Repository:** [Blogger-With-Django](https://github.com/Mohammed-Elkhamlichi/Blogger-With-Django)

## ✨ Features

- 📰 Blog post listing and detail pages
- ✍️ Blog content creation and management
- 👤 User authentication, if implemented
- 🗂️ Organized blog content
- 🛠️ Django administration support
- 🎨 Dynamic web pages using Django templates

*Confirm which features are implemented in your code before publishing this list.*

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, JavaScript
- **Templating:** Django Template Language
- **Database:** SQLite by default, if configured in the project
- **Version Control:** Git and GitHub

## 📂 Project Structure

```text
Blogger-With-Django/
├── blog/             # Blog application functionality
├── templates/        # HTML templates
├── static/           # CSS, JavaScript, and other static assets
├── media/            # Uploaded media files, if applicable
├── manage.py         # Django management utility
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
```

*Adapt the directory names to match your repository.*

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

- [Python](https://www.python.org/downloads/)
- pip
- [Git](https://git-scm.com/)

### 1. Clone the repository

```bash
git clone https://github.com/Mohammed-Elkhamlichi/Blogger-With-Django.git
```

### 2. Navigate to the project directory

```bash
cd Blogger-With-Django
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

On macOS or Linux:

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 5. Apply database migrations

```bash
python manage.py migrate
```

### 6. Create an administrator account

```bash
python manage.py createsuperuser
```

Follow the prompts to create your credentials.

### 7. Run the development server

```bash
python manage.py runserver
```

Open the application in your browser:

[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

The Django administration interface is usually available at:

[http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

*These instructions assume the repository includes `manage.py` and `requirements.txt`. The administrator interface also requires Django's admin URLs to be configured.*

## 🖼️ Screenshots

Add screenshots to demonstrate the application's design and functionality.

For example:

```markdown
![Blogger Homepage](screenshots/homepage.png)
![Blog Post Detail](screenshots/post-detail.png)
```

## 🎯 What I Learned

- Developing web applications with Django
- Working with Django models, views, and templates
- Integrating application logic with a database
- Managing Python dependencies and virtual environments
- Organizing a Django project into reusable components

## 👨‍💻 Author

**Mohammed El Khamlichi**

- GitHub: [@Mohammed-Elkhamlichi](https://github.com/Mohammed-Elkhamlichi)
- LinkedIn: [Connect with me](https://www.linkedin.com/)

## 📄 License

Check the repository for an existing license. If no license is present, reuse and distribution permissions should not be assumed.
