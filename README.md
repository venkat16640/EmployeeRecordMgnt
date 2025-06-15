# Employee Record Management System

A Django-based web application for managing employee records, including personal information, education, and work experience.

## Features

- Employee registration and profile management
- Education and experience tracking
- Admin dashboard for employee management
- Secure authentication system
- Responsive design

## Technology Stack

- Python 3.8+
- Django
- SQLite (Development)
- HTML/CSS
- Bootstrap

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/venkat16640/EmployeeRecordMgnt.git
   cd EmployeeRecordMgmt
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

7. Access the application at `http://localhost:8000`

## Project Structure

- `EmployeeRecordMgmt/` - Main project directory
  - `employee/` - Employee management app
    - `templates/` - HTML templates
    - `static/` - CSS, JavaScript, and images
    - `models.py` - Database models
    - `views.py` - View logic
  - `manage.py` - Django management script

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 