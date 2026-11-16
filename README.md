# ✈️ Flight Ticket Booking System

A web-based Flight Ticket Booking System developed using **Python and Django**. This application allows users to register, log in, search for available flights, book tickets, manage their bookings, and update their profiles.

## 🚀 Features

- User registration and login
- User logout and password management
- Search flights by source and destination
- View flight details, schedules, and prices
- Book flight tickets
- View personal booking history
- Update passenger and ticket details
- Cancel flight bookings
- Update user profile information
- Django admin panel for flight management
- SQLite database integration
- HTML and CSS-based user interface

## 🛠️ Technology Stack

| Technology | Purpose |
| --- | --- |
| Python | Backend programming |
| Django | Web framework |
| HTML5 | Frontend structure |
| CSS3 | Frontend styling |
| SQLite | Database |
| Django Templates | Dynamic web pages |

## 📁 Project Structure

text

```text
Flight-Ticket-Booking-System/
│
├── myproject/
│   ├── authen/
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── forms.py
│   │   └── urls.py
│   │
│   ├── base/
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── forms.py
│   │   ├── urls.py
│   │   ├── templates/
│   │   └── static/
│   │
│   ├── myproject/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   │
│   ├── manage.py
│   └── db.sqlite3
│
└── README.md
```

## ⚙️ Installation and Setup

### 1\. Clone the repository

bash

```bash
git clone https://github.com/rockstarrk04/Flight-Ticket-Booking-System.git
```

### 2\. Navigate to the project directory

bash

```bash
cd Flight-Ticket-Booking-System
```

### 3\. Create a virtual environment

bash

```bash
python -m venv venv
```

Activate the virtual environment.

**Windows:**

bash

```bash
venv\Scripts\activate
```

**macOS/Linux:**

bash

```bash
source venv/bin/activate
```

### 4\. Install Django

bash

```bash
pip install django
```

### 5\. Navigate to the Django project directory

bash

```bash
cd myproject
```

### 6\. Apply database migrations

bash

```bash
python manage.py migrate
```

### 7\. Create a superuser

bash

```bash
python manage.py createsuperuser
```

Follow the instructions to create your administrator account.

### 8\. Run the development server

bash

```bash
python manage.py runserver
```

Open your browser and visit:

**http://127.0.0.1:8000/**

## 🌐 Application URLs

| Feature | URL |
| --- | --- |
| Login | `/` |
| Registration | `/register/` |
| Logout | `/logout/` |
| Change Password | `/change_password` |
| Flight Search | `/base/` |
| User Profile | `/base/profile/` |
| My Bookings | `/base/bookings/` |
| Admin Panel | `/admin/` |

## 📌 How to Use

1. Open the application in your browser.
2. Register a new user account.
3. Log in using your credentials.
4. Search for flights by entering the source and destination.
5. Select your preferred available flight.
6. Enter the required passenger details.
7. Confirm your ticket booking.
8. Visit the bookings section to view and manage your reservations.
9. Update your profile whenever required.

## 🗄️ Database

This project uses **SQLite** as its default database.

The database file is:

text

```text
myproject/db.sqlite3
```

Django ORM is used to interact with the database.

## 🧪 Running Tests

To execute the Django test suite, run:

bash

```bash
python manage.py test
```

## 🔮 Future Enhancements

- Online payment gateway integration
- Email booking confirmations
- PDF ticket generation
- Real-time seat availability
- Advanced flight search and filtering
- Unique booking reference numbers
- REST API integration
- Improved automated testing
- Production deployment

## 🔐 Security Considerations

Before deploying the application to production:

- Set `DEBUG = False`.
- Store the Django secret key in environment variables.
- Configure `ALLOWED_HOSTS`.
- Use HTTPS.
- Configure a production-ready database.
- Implement appropriate booking ownership and authorization checks.
- Protect sensitive passenger information.

## 🤝 Contributing

Contributions are welcome\!

1. Fork this repository.
2. Create a new feature branch.
3. Make your changes.
4. Commit your changes.
5. Push your branch.
6. Submit a pull request.

## 👨‍💻 Author

**Rockstar RK04**

GitHub: [@rockstarrk04](<https://github.com/rockstarrk04>)

---

⭐ If you find this project useful, consider giving it a star on GitHub\!

**Developed with Python and Django.**

Note: Save this content in `README.md` at the repository root (`Flight-Ticket-Booking-System/README.md`), not inside the nested `myproject` directory.
