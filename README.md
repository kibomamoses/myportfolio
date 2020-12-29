# myportfolio
# How To Setup On Linux
Clone This Project git clone https://github.com/sajib1066/makeportfolio.git
Go to Project Directory cd makeportfolio
Create a Virtual Environment python3 -m venv env
Activate Virtual Environment source env/bin/activate
Install Requirements Package pip install -r requirements.txt
Migrate Database python manage.py migrate
Create Super User python manage.py createsuperuser
Finally Run The Project python manage.py runserver
