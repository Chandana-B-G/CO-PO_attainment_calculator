# CO-PO_attainment_calculator
This repository hosts the CO-PO Attainment Calculator, a web app that simplifies and automates the calculation of Course Outcomes (COs) and Program Outcomes (POs) for academic institutions, ensuring accuracy and efficiency.
Features

User-friendly interface for CO and PO calculation.
Admin panel for managing teachers and data.
Secure login for teachers.
Installation

Follow these steps to set up and run the project:

Create a Python Virtual Environment To isolate dependencies and ensure smooth setup:

python -m venv env

Activate the virtual environment:

Windows: .\env\Scripts\activate
Linux/Mac: source env/bin/activate
Install Required Dependencies
Download the necessary libraries listed in requirements.txt:

pip install -r requirements.txt
Apply Migrations
Run the following commands to apply database migrations:

python manage.py makemigrations
python manage.py migrate
Create a Superuser
Create an admin user for accessing the Django admin panel:

python manage.py createsuperuser
Follow the prompts to set the username, email, and password.

Add Teachers in the Admin Panel

Log in to the admin panel at: http://127.0.0.1:8000/admin/

Use the superuser credentials to log in.

Navigate to the Teachers section and add teachers with their credentials.

Teacher Login

Go to the login page: http://127.0.0.1:8000/login/

Enter the credentials for a teacher account.

Start using the platform for COPO calculation!

Contributing

If you'd like to contribute, please fork the repository and create a pull request.

License

This project is licensed under the MIT License.
