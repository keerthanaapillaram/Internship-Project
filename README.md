# 🐾 Pet Care Shop – Full Stack Django Project  

### This is a full-stack web application developed as part of an internship project at Retech Solutions. The system provides a platform for a Pet Care Shop to manage its services, products, and customer interactions online.

### 🚀 Key Features
User Authentication: Secure user registration, login, and profile management.

Pet & Product Listings: Browse available pets, accessories, and pet care products.

Service Booking: Schedule appointments for veterinary check-ups or grooming services.

Shopping Cart & Checkout: A fully functional cart system for placing orders.

Admin Dashboard: An administrative interface for managing inventory, users, and appointments.

### 📁 Project Structure
The project follows a standard Django application structure:
```
pet-care-shop-django/
│
├── petcare/            # Core Django project configuration
│   ├── settings.py
│   └── urls.py
│
├── shop/               # App for products, services, and core logic
│   ├── models.py
│   ├── views.py
│   ├── templates/
│   └── static/
│
├── users/              # App for user authentication and profiles
│   ├── models.py
│   ├── views.py
│   └── templates/
│
├── manage.py           # Django's command-line utility
└── requirements.txt    # Project dependencies
```

### 🛠️ Tech Stack
Backend: Python, Django

Frontend: HTML, CSS, JavaScript (with potential for Bootstrap)

Database: SQLite3 (for development)

Version Control: Git & GitHub

### ⚙️ Local Development Setup
Follow these steps to get the project running on your local machine.

1. Clone the Repository
```git
git clone [https://github.com/keerthanaapillaram/Internship-Project 
cd pet-care-shop-django
```

2. Create and Activate a Virtual Environment
A virtual environment keeps your project dependencies isolated.
```
On macOS/Linux:

python3 -m venv venv
source venv/bin/activate

On Windows:

python -m venv venv
.\venv\Scripts\activate
```

3. Install Dependencies
Install all the required packages from the requirements.txt file.

pip install -r requirements.txt

4. Apply Database Migrations
Create the database schema based on your app models.
```
python manage.py migrate
```
5. Create a Superuser
This creates an admin account to access the Django admin dashboard.
```
python manage.py createsuperuser
```
Follow the prompts to set up your username and password.

6. Run the Development Server
Start the application.
```
python manage.py runserver
```
The project will be available at http://127.0.0.1:8000/. You can access the admin dashboard at http://127.0.0.1:8000/admin/.


📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
