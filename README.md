# externalDB-MySql-Django
External MySQL Db is deployed in the project Steps:

Install Xampp Server.
Start apache & MySQL.
Add new database name.
Run the cmnd: pip install mysqlclient
Replace Database dictionary with: DATABASES = { 'default': { 'ENGINE': 'django.db.backends.mysql', 'NAME': 'dataflair', 'USER': 'root', 'PASSWORD': “”, 'HOST': “”, 'PORT': “”, 'OPTIONS': { 'init_command': "SET sql_mode='STRICT_TRANS_TABLES'" } } }
Finally run the cmnds: python manage.py migrate python manage.py runserver
