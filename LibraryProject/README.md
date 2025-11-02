# Introduction to Django – Task 0

LibraryProject Setup

## Objective

Set up the initial Django development environment and create a Django project named `LibraryProject`.

## Requirements

- Python installed on the system
- Django installed via pip
- GitHub repository: `Alx_DjangoLearnLab`
- Directory: `Introduction_to_Django`

## Steps Taken

### 1. Installed Django

Verified Python installation, then installed Django:

```bash
pip install django
Confirmed installation:

bash
Copy code
python -m django --version
2. Created Django Project
From the project directory:

bash
Copy code
python -m django startproject LibraryProject
This generated the default Django project structure.

3. Explored Project Structure
csharp
Copy code
LibraryProject/
│
├── LibraryProject/
│   ├── __init__.py
│   ├── settings.py      # Main configuration file
│   ├── urls.py          # URL routing file
│   ├── asgi.py
│   └── wsgi.py
│
└── manage.py            # Command-line management utility
4. Ran the Development Server
Navigated into the project folder and started the server:

bash
Copy code
cd LibraryProject
python manage.py runserver
Opened a browser and accessed:

cpp
Copy code
http://127.0.0.1:8000/
Django welcome page loaded successfully, confirming setup.

Outcome
The Django environment is successfully set up, the LibraryProject was created, and the default Django server ran without issues. This completes Task 0 of Introduction to Django.

yaml
Copy code
```
