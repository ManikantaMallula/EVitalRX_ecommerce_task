# EVitalRX_ecommerce_task

# E-commerce Platform

An e-commerce platform built with Django and Django REST Framework, featuring user authentication with JWT, product and review management, and integration with AWS S3 for media storage.

## Features

- User registration, login, and logout with JWT authentication.
- Product and category management.
- Review system for products.
- Soft delete for products.
- Integration with AWS S3 for media storage.
- API documentation with Swagger and ReDoc.

## Requirements

- Python 3.x
- Django 5.0.3
- Django REST Framework
- Django Filters
- Django Storages
- Boto3
- DRF-YASG

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/ecommerce-platform.git
   cd ecommerce-platform

python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

pip install -r requirements.txt

AWS_ACCESS_KEY_ID = 'your-access-key-id'
AWS_SECRET_ACCESS_KEY = 'your-secret-access-key'
AWS_STORAGE_BUCKET_NAME = 'your-bucket-name'

python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
