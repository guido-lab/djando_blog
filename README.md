# django-blog

## How to setup:
Clone This Project (Make Sure You Have Git Installed)
```
https://github.com/mustafamuratcoskun/django-blog.git
```

The following command creates a new virtual environment named venv in the current directory

```bash
$ python -m venv env
```

Activate virtual environment:

```bash
(Mac/Linux) $ source env/bin/activate
```

```bash
(Windows) $ source env/Scripts/activate
```

Install Dependencies 

```
pip install -r requirements.txt
```

Set Database (Make Sure you are in directory same as manage.py)
```
python manage.py makemigrations
python manage.py migrate
```
Create SuperUser 
```
python manage.py createsuperuser
```

Run the development server:

```bash
python manage.py runserver
```

The project is runing at: **http://127.0.0.1:8000/**

Access admin pannel: **http://127.0.0.1:8000/admin**

