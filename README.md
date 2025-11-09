Unity Graphics

A Full-Stack Django E-Commerce Website for Digital Design Assets

🧾 Overview

Unity Graphics is a full-stack eCommerce web application built with the Django framework.
It provides a digital marketplace for designers and creators to sell, manage, and deliver digital assets such as templates, fonts, illustrations, and icons.

The platform supports user authentication, product uploads, a shopping cart system, admin management, and REST API endpoints for future integrations.

🚀 Features

🧑‍💻 User Authentication – Register, Login, Logout using Django Auth.

🎨 Product Management – Admin can add, update, or delete digital design assets.

🛒 Shopping Cart – Add products, view cart, and checkout.

💾 Digital Downloads – Users can download purchased digital files securely.

🔒 Admin Dashboard – Manage users, orders, and product listings.

🔗 REST API – Built with Django REST Framework for mobile and external app integration.

🌐 Responsive Design – Built with HTML, CSS, and JavaScript for smooth UX.

☁️ Deployment Ready – Configured with Gunicorn & Whitenoise for production.

🧰 Tech Stack
Layer	Technology
Frontend	HTML5, CSS3, JavaScript
Backend	Python (Django Framework)
Database	SQLite3 (Development) / PostgreSQL (Production)
API	Django REST Framework
Server	Gunicorn + Whitenoise
Version Control	Git & GitHub
Design Tools	Photoshop, Figma





PROJECT STRUCTURE

unitygraphics/
├── manage.py
├── unitygraphics/           # Django project configuration
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── home/                    # Main app (Frontend + Products)
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/home/
│   └── static/home/
│
├── accounts/                # User authentication module
│   ├── views.py
│   ├── urls.py
│   └── templates/registration/
│
├── api/                     # REST API module
│   ├── serializers.py
│   ├── views.py
│   └── urls.py
│
├── templates/               # Base templates
│   └── base.html
└── requirements.txt

