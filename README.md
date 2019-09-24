# Flask Login, Logout and Sign Up Application

A Basic Flask Application to login, logout and sign up user.

## Prerequisites:

You will need the following programmes properly installed on your computer.

* [Python](https://www.python.org/) 3.6+
* [Postgres](https://www.postgresql.org/)

To install virtual environment on your system use:

```bash
sudo apt-get install python3-venv -y

## Installation:

```bash
git clone https://github.com/ongraphpythondev/flask-app.git

cd flask-app

python3 -m venv venv

source venv/bin/activate

# install required packages for the project to run
pip install -r requirements.txt
```
Configure database setting
* Open instance/config.py

* SQLALCHEMY_DATABASE_URI = 'postgresql://postgres_user:postgres_password@localhost/postgres_db'


## Running:

To run the development server after installation:
```bash


# run server
$ export FLASK_CONFIG=development
$ export FLASK_APP=run.py
$ flask db migrate
$ flask db upgrade
$ flask run
```

