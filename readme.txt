Python==2.7.10

MySQL==5.7.9		# root@localhost: &r)BXl1aeChE
# sudo /usr/local/mysql/support-files/mysql.server start
# sudo /usr/local/mysql/support-files/mysql.server stop
mysql-python==1.2.3

PostgreSQL==9.4.4	# postgres: postgres
psycopg2==2.5.5

Django==1.8.6

django-admin startproject alarmreport

python manage.py syncdb
python manage.py createsuperuser # admin: admin
python manage.py runserver 8080

python manage.py startapp report
python manage.py makemigrations report
python manage.py migrate report

python manage.py test report

