1 - start_postgres
2 - pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1
3 - (at the ORM django directory)
pip install virtualenv

virtualenv djangoenv

source djangoenv/bin/activate
4- pip install django==4.2.4 psycopg2-binary==2.9.7
5-python3 manage.py makemigrations standalone
6- python3 manage.py migrate
7-python3 test.py
