# E - Journal

[![Українська](https://img.shields.io/badge/Мова-Українська-blue)](README.md)

## Description.

This project is a web application for logging, built with Django.


## Install and run


1. Clone the repository:
   ## bash
   git clone https://github.com/vitaliikovalkovskyi/E-Journal.git

2. Change to the project directory:
   ```bash
   cd E-Journal

3. Create a virtual environment at the desired level (at the root of the project):
   ```bash
   python -m venv venv

4. Activate the virtual environment:
   ```bash
   ./Scripts/activate

5. Change to the journal directory:
   ```bash
   cd journal

6. Install the dependencies:
   ```bash
   pip install -r requirements.txt

7. Perform the migration:
   ```bash
   python manage.py migrate

8. Start the server
   ```bash
   python manage.py runserver

## Usage
Open a web browser and go to http://127.0.0.1:8000/ to view the application.
## Project structure
manage.py: The main file for managing the project.
journal/: The main project configuration.
journal_app/: The main application logic.
templates/: HTML templates.
static/: Static files (CSS, JS, images).
## License
This project is licensed under the MIT license.

