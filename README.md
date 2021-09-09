# django-todolist

Simple todolist write in django for general use and pipeline automation..

  - Be kind with my baby

### Quick and free tip:

> With great power comes great responsibility


### Requirements for ubuntu

Instalar o python3-pip

$ sudo apt-get install python3-pip

Instalar o mysqlclient

$ sudo apt-get update
$ sudo apt-get install mysql-client
$ sudo apt-get install python3-dev default-libmysqlclient-dev build-essential # Debian /

### Instalando o venv

$ sudo pip3 install virtualenv nose coverage nosexcover pylint

### Criando e ativando o venv (dev)

cd ../    

$ virtualenv  --always-copy  venv-django-todolist
$ source venv-django-todolist/bin/activate
$ pip install -r requirements.txt

### Tech

Dillinger uses a number of open source projects to work properly:

* [Django] - Django makes it easier to build better Web apps more quickly and with less code.
* [Python-Venv] - The venv module provides support for creating lightweight “virtual environments” with their own site directories
* [MySQL] - MySQL is an Oracle-backed open source relational database management system (RDBMS) based on Structured Query Language (SQL).


### Installation

Install the dependencies and start the server.

```sh
$ cd django-todolist
$ pip install -r requirements.txt
$ python manage.py migrate # Running the migrations
$ python manage.py createsuperuser # Create a superuser
$ python manage.py runserver 0:8000
```


License
----

GPL
