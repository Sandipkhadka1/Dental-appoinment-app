# Dental Clinic Appointment System (60% MVP)

This project has been trimmed down to a smaller, working MVP version of the dental clinic system. It focuses on the core workflow only and intentionally excludes the more advanced modules that were not needed for the first delivery.

## Almost 60% Completed

- User accounts and login/register flow
- Patient management
- Dentist management
- Appointment booking and basic dashboard views
- Admin controls for users and approvals

## Not from the active scope

- Service catalog features
- Reminder management module
- Reporting module
- Extra advanced workflow components

## Run locally

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/macOS
source venv/bin/activate

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open http://127.0.0.1:8000/ in your browser.

## Optional future upgrade

This can be expanded later with live doctor notifications, reminder automation, and reporting dashboards once the core clinic flow is stable. 