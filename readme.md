Let's build a simple blog, with the Python Web Framework [Django](https://www.djangoproject.com)!
---
![Django Logo](/media/django_logo.png)

This Project is about building a simple Blog Website with the Python Web Framework 'DJANGO'.

It's made for a friend of mine, to support him sharing his impressions and thoughts, when traveling through columbia. 

The Frontend is kept simple and therefore only uses HTML & CSS. 

### Get started

##### 1. Clone everything to your local disk with

```
git clone https://github.com/ErikUckert/django-demo.git
```

##### 2. Get yourself a python 3 version up and running on your machine

##### 3. Create a virtual environment in your working directory

```
python3 -m venv /path/to/new/virtual/environment
```

##### 4. Run this virtual environment

```
source /path/to/new/virtual/environment/bin/activate
```

##### 5. Navigate to the cloned repository directory and run migration

```
python3 manage.py migrate
```

##### 6. Set up an admin user for creating blog posts

```
python3 manage.py createsuperuser
```

##### 7. Run the server and visit local host adress in your webbrowser (127.0.0.1:8000 usualy, but it's shown in the open console)
```
python3 manage.py runserver
```



