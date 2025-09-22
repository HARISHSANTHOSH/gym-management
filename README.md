# Gym Management System

A comprehensive gym management system built with Django that helps gym owners and members manage workouts, track progress, and maintain fitness goals.

## Features (Planned)

### Phase 1: Core Foundation
- [x] Django project setup
- [ ] User authentication system
- [ ] Basic user profiles

### Phase 2: Core Gym Features
- [ ] Workout management
- [ ] Exercise database
- [ ] Workout history

### Phase 3: Progress Tracking
- [ ] Progress tracking
- [ ] Statistics & analytics
- [ ] Goal setting

### Phase 4: Social Features
- [ ] Friend system
- [ ] Workout sharing
- [ ] Community challenges

### Phase 5: Advanced Features
- [ ] Nutrition tracking
- [ ] Meal planning
- [ ] Mobile responsiveness

## Tech Stack

- **Backend**: Django 4.2, Django REST Framework
- **Database**: PostgreSQL (production), SQLite (development)
- **Frontend**: HTML, CSS, JavaScript (Bootstrap)
- **Authentication**: Django's built-in auth system
- **Deployment**: Ready for Heroku/Railway deployment

## Getting Started

### Prerequisites
- Python 3.8+
- pip
- virtualenv

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd gym
```

2. Create and activate virtual environment:
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Create superuser:
```bash
python manage.py createsuperuser
```

6. Run development server:
```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` to see the application.

## Project Structure

```
gym/
├── manage.py
├── requirements.txt
├── README.md
├── .gitignore
├── gym/                 # Main project directory
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
└── gymapp/              # Main Django app
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── views.py
    ├── tests.py
    └── migrations/
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License

This project is licensed under the MIT License.
