install redis-server 3.0.7


clone source code and cd to it.
then please run these commands: 
- python3.6 -m venv env

- source env/bin/activate
 
- pip install django==1.11 channels==1.1.8 asgi_redis==1.4.3 celery==4.1

- cd example_channels/

- python manage.py migrate

- python manage.py runserver 8777


open browser and access to your : http://localhost:8777