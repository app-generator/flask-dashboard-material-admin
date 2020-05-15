# [Flask Dashboard Material Admin](https://appseed.us/admin-dashboards/flask-dashboard-admin-material)

> **Open-Source Admin Dashboard** coded in **Flask Framework** by **AppSeed** [Web App Generator](https://appseed.us/app-generator) - Features:

- UI Kit: **[Material Admin](https://flask-dashboard-material-admin.appseed.us/login)** (Free version) provided by **BootstrapDash**
- Modular design with **Blueprints**
- SQLite, PostgreSQL, SQLAlchemy ORM
- Alembic (DB schema migrations)
- Session-Based authentication (via **flask_login**)
- Deployment scripts: Docker, Gunicorn / Nginx
- **MIT License**
- Free support via **Github** 
- Paid Support **24/7 LIVE Support** via [Discord](https://discord.gg/fZC6hup)

> Links

- [Flask Dashboard Material Admin](https://appseed.us/admin-dashboards/flask-dashboard-admin-material) - Product page
- [Flask Dashboard Material Admin](https://docs.appseed.us/admin-dashboards/flask-dashboard-material-admin/) - Documentation
- [Flask Dashboard Material Admin](https://flask-dashboard-material-admin.appseed.us/login) - LIVE Demo
- More [Flask Admin Dashboards](https://appseed.us/admin-dashboards/flask) - index hosted by **AppSeed**
- [Free Admin Dashboards](https://appseed.us/admin-dashboards/open-source) - index hosted by **AppSeed**

<br />

## Want more? Go PRO!

PRO versions include **Premium UI Kits**, Lifetime updates and **24/7 LIVE Support** (via [Discord](https://discord.gg/fZC6hup))

| [Flask DattaAble Dark PRO](https://appseed.us/admin-dashboards/flask-dashboard-dattaable-dark-pro) | [Flask Dashboard Black PRO](https://appseed.us/admin-dashboards/flask-dashboard-black-pro) | [Flask StarAdmin Dark PRO](https://appseed.us/admin-dashboards/flask-dashboard-staradmin-black-pro) |
| --- | --- | --- |
| [![Flask DattaAble Dark PRO](https://raw.githubusercontent.com/app-generator/flask-dashboard-dattaable-dark-pro/master/media/flask-dashboard-dattaable-dark-pro-screen.png)](https://appseed.us/admin-dashboards/flask-dashboard-dattaable-dark-pro) | [![Flask Dashboard Black PRO](https://raw.githubusercontent.com/app-generator/flask-dashboard-black-pro/master/media/flask-dashboard-black-pro-screen.png)](https://appseed.us/admin-dashboards/flask-dashboard-black-pro) | [![Flask StarAdmin Dark PRO](https://raw.githubusercontent.com/app-generator/flask-dashboard-staradmin-black-pro/master/media/flask-dashboard-staradmin-black-pro-screen.png)](https://appseed.us/admin-dashboards/flask-dashboard-staradmin-black-pro)

<br />
<br />

![Flask Dashboard Material Admin - Open-Source Dashboard.](https://raw.githubusercontent.com/app-generator/static/master/products/flask-dashboard-material-admin-screen.png)

<br />

## How to use it

```bash
$ # Get the code
$ git clone https://github.com/app-generator/flask-dashboard-material-admin.git
$ cd flask-dashboard-material-admin
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ # Install modules - SQLite Database
$ pip3 install -r requirements.txt
$
$ # OR with PostgreSQL connector
$ # pip install -r requirements-pgsql.txt
$
$ # Set the FLASK_APP environment variable
$ (Unix/Mac) export FLASK_APP=run.py
$ (Windows) set FLASK_APP=run.py
$ (Powershell) $env:FLASK_APP = ".\run.py"
$
$ # Set up the DEBUG environment
$ # (Unix/Mac) export FLASK_ENV=development
$ # (Windows) set FLASK_ENV=development
$ # (Powershell) $env:FLASK_ENV = "development"
$
$ # Start the application (development mode)
$ # --host=0.0.0.0 - expose the app on all network interfaces (default 127.0.0.1)
$ # --port=5000    - specify the app port (default 5000)  
$ flask run --host=0.0.0.0 --port=5000
$
$ # Access the dashboard in browser: http://127.0.0.1:5000/
```

<br />

## Deployment

The app is provided with a basic configuration to be executed in [Docker](https://www.docker.com/), [Gunicorn](https://gunicorn.org/), and [Waitress](https://docs.pylonsproject.org/projects/waitress/en/stable/).

<br />

### [Docker](https://www.docker.com/) execution
---

The application can be easily executed in a docker container. The steps:

> Get the code

```bash
$ git clone https://github.com/app-generator/flask-dashboard-material-admin.git
$ cd flask-dashboard-material-admin
```

> Start the app in Docker

```bash
$ sudo docker-compose pull && sudo docker-compose build && sudo docker-compose up -d
```

Visit `http://localhost:5005` in your browser. The app should be up & running. 

<br />

### [Gunicorn](https://gunicorn.org/)
---

Gunicorn 'Green Unicorn' is a Python WSGI HTTP Server for UNIX.

> Install using pip

```bash
$ pip install gunicorn
```
> Start the app using gunicorn binary

```bash
$ gunicorn --bind 0.0.0.0:8001 run:app
Serving on http://localhost:8001
```

Visit `http://localhost:8001` in your browser. The app should be up & running.


<br />

### [Waitress](https://docs.pylonsproject.org/projects/waitress/en/stable/)
---

Waitress (Gunicorn equivalent for Windows) is meant to be a production-quality pure-Python WSGI server with very acceptable performance. It has no dependencies except ones that live in the Python standard library.

> Install using pip

```bash
$ pip install waitress
```
> Start the app using [waitress-serve](https://docs.pylonsproject.org/projects/waitress/en/stable/runner.html)

```bash
$ waitress-serve --port=8001 run:app
Serving on http://localhost:8001
```

Visit `http://localhost:8001` in your browser. The app should be up & running.

<br />

## Credits & Links

<br />

## What is [Flask](https://www.palletsprojects.com/p/flask/)

[Flask](https://www.palletsprojects.com/p/flask/) is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as a simple wrapper around Werkzeug and Jinja and has become one of the most popular Python web application frameworks.

<br />

### [What is a dashboard](https://en.wikipedia.org/wiki/Dashboard_(business))

A dashboard is a set of pages that are easy to read and offer information to the user in real-time regarding his business. A dashboard usually consists of graphical representations of the current status and trends within an organization. Having a well-designed dashboard will give you the possibility to act and make informed decisions based on the data that your business provides - *definition provided by [Creative-Tim - Free Dashboard Templates](https://www.creative-tim.com/blog/web-design/free-dashboard-templates/?ref=appseed)*.

<br />

### [Material Admin](https://www.bootstrapdash.com/product/material-design-template-free/)

Material Admin is a free admin template that is entirely built using the framework Google’s Material Design for the Web to comply with the Material Design guidelines. It comes with the basic components and set of pre-built pages required to lay the foundation for any application - provided by **BootstrapDash**.

<br />

---
**[Flask Dashboard Material Admin](https://appseed.us/admin-dashboards/flask-dashboard-admin-material)** - Provided by **AppSeed** [Web App Generator](https://appseed.us/app-generator).
