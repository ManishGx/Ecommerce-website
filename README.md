# E-Commerce Platform

A Django-based e-commerce platform built to learn and demonstrate backend web development concepts.

## Features

- Category management
- Product management
- Product images
- Product stock tracking
- Product availability status
- SEO-friendly slugs
- Django Admin customization

## Tech Stack

- Python
- Django
- SQLite
- HTML
- CSS
- Bootstrap

## Project Structure

Ecomm-Platform/
│
├── manage.py
├── README.md
├── .gitignore
│
├── ecomm/                    # Main project configuration
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── accounts/                 # User authentication & profiles
│   ├── models.py
│   ├── views.py
│   ├── admin.py
│   └── migrations/
│
├── category/                 # Product categories
│   ├── models.py
│   ├── views.py
│   ├── admin.py
│   └── migrations/
│
├── store/                    # Product management
│   ├── models.py
│   ├── views.py
│   ├── admin.py
│   └── migrations/
│
├── templates/
│   ├── base.html
│   ├── home.html
│   └── includes/
│       ├── navbar.html
│       └── footer.html
│
├── static/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── fonts/
│
└── media/
    └── photos/



## Current Progress

- [x] Django project setup
- [x] Category model
- [x] Product model
- [x] Django Admin configuration
- [ ] Product listing page
- [ ] Product detail page
- [ ] Shopping cart
- [ ] User authentication
- [ ] Checkout system

## Installation

```bash
git clone <repository-url>
cd ecomm
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver