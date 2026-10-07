# Env Billing

A Django-based billing and invoice management web application designed to simplify the process of creating, managing, and tracking bills.

## Features

- Create and manage customer billing records
- Generate and manage invoices
- Store billing information efficiently
- Django-based backend architecture
- User-friendly web interface
- Database integration using Django ORM
- Organized and scalable project structure

## Tech Stack

- **Python**
- **Django**
- **HTML / CSS**
- **JavaScript**
- **SQLite** (development database)

## Project Structure

```text
env_billing/
│
├── manage.py
├── requirements.txt
│
├── billing/
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   └── ...
│
├── templates/
├── static/
└── ...
```

> The virtual environment (`venv`) is not included in the repository. It can be recreated using the project dependencies.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/varshith2323/env-billing.git
cd env-billing
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run database migrations

```bash
python manage.py migrate
```

### 6. Start the development server

```bash
python manage.py runserver
```

Open the application in your browser:

```text
http://127.0.0.1:8000/
```

## Usage

After starting the Django development server, open the application in your browser and use the available billing features to create and manage billing records.

## Future Improvements

- User authentication and role-based access
- PDF invoice generation
- Online payment integration
- Customer management dashboard
- Sales and revenue analytics
- Email invoice functionality
- Deployment to a cloud platform

## Author

**Varshith Raj Pittala**

## License

This project is available for educational and development purposes.
