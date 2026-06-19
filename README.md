# Inventory & Billing System

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.0-brightgreen.svg)](https://www.djangoproject.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0-purple.svg)](https://getbootstrap.com/)

A full-featured inventory management and billing system built with Django, Python, CSS, and Bootstrap. This system helps businesses track inventory, manage products, generate bills, and view sales reports.


## Features

- 🏷️ Product catalog management
- 📊 Real-time inventory tracking
- 🧾 Invoice generation
- 📈 Sales reporting and analytics
- 👥 User management system
- 🔍 Advanced search functionality
- 📱 Responsive design for all devices

## Technology Stack

- **Backend**: Django (Python)
- **Frontend**: HTML5, CSS3, Bootstrap 5
- **Database**: SQLite (default) - can be configured for PostgreSQL/MySQL
- **Authentication**: Django built-in auth system

## Installation

Follow these steps to set up the project locally:

### Prerequisites
- Python 3.8+
- pip (Python package manager)
- Virtualenv (recommended)

### Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/sachink2103/inventory_billing_system.git
cd inventory_billing_system


Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install dependencies:
pip install -r requirements.txt

Run migrations:
python manage.py migrate

Create a superuser (admin account):
python manage.py createsuperuser

Run the development server:
python manage.py runserver

Access the application at **http://127.0.0.1:8000**


**Usage Guide
Admin Panel
Access the Django admin interface at /admin using your superuser credentials to:**

Manage products and inventory
View and manage users
Access sales reports
End-User Features
Product Management:

Add/edit/delete products
Set categories and pricing
Track stock levels
Billing System:

Generate invoices
Print receipts
View transaction history
Reports:

Daily sales reports
Inventory alerts
Sales analytics


**License**
This project is licensed under the MIT License - see the LICENSE file for details.


**Contact
For support or questions, please contact:**


Rakshitha S- rakshithayadav295@gmail.com
GitHub: https://github.com/Rakshitha-S-018
Project Link: https://github.com/Rakshitha-S-018/inventory-billing-system

