# SSO Project

This project is a Single Sign-On (SSO) application developed using the Django framework. Users can access multiple applications with a single sign-on.

## Getting Started

This guide provides steps to run the project on your local machine.

### Prerequisites

Ensure the following software is installed on your computer:

- Python 3.8 or higher
- Django 3.2 or higher

### Installation

Step-by-step installation instructions:

1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
2. Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # Unix/Mac
venv\Scripts\activate  # Windows

3.Install the required dependencies:
     pip install -r requirements.txt

4. Apply database migrations:

   python manage.py migrate

5. Start the development server
   python manage.py runserver





Usage
Once the server is running, open your web browser and go to http://127.0.0.1:8000/.

Project Structure

manage.py: Django management command.
sso/: Main application folder.
templates/: HTML template files.
db.sqlite3: SQLite database file.
Contributing

To contribute, please follow these steps:

Fork the project.
Create a new branch: git checkout -b new-feature.
Commit your changes: git commit -m 'Add new feature'.
Push to the branch: git push origin new-feature.
Create a Pull Request.
