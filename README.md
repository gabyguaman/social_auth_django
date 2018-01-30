// create a virtual environment
virtualenv venv

// activate the environment
source ./venv/bin/activate

// install the requirements
pip install -r requirements.txt

// create the database and a superuser
python manage.py syncdb

// run the application
python manage.py runserver
