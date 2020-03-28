# Portfolio-Application
A simple portfolio application built using Django Framework.

### Setting up Virtual Environment and Install Requirements
```bash
sudo pip install virtualenv
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### How to run the project
```bash
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Use the admin feature to add projects or blog articles as you do not want users to add anything to your portfolio :)