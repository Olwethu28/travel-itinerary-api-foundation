# Travel Itinerary Planning & Booking API

Django + Django REST Framework capstone project.

## Current milestone

The repository currently contains the project foundation:

- Django project and six required apps
- DRF, JWT, filtering and OpenAPI dependencies
- Environment-based settings
- Custom User model
- Registration and profile endpoints
- JWT token endpoints
- Swagger/OpenAPI configuration
- pytest configuration

## Setup

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env.example .env
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

Swagger: `/api/docs/`

## Build order

1. Foundation and authentication
2. Destination and itinerary models
3. Booking and activity models
4. Reviews and budgets
5. Serializers
6. Permissions and roles
7. ViewSets and custom actions
8. Filtering/search/pagination
9. Query optimization
10. Tests and coverage
11. Final rubric audit
