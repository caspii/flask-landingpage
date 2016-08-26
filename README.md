# Landing page
* This is a very lightweight landing page offering email signup implemented using Flask and sqlite


# Setup
1. Install packages `sudo apt install python-pip python-virtualenv python-dev`
2. Create a python virtual environment: `virtualenv venv`
3. Enter virtual environment: `source venv/bin/activate`
3. Install python packages `pip install -r requirements.txt`
4. Initialize database: `export FLASK_APP=landing.py && flask initdb`
5. Run app in debug mode locally using `run.sh`

Also See here: http://flask.pocoo.org/docs/0.11/installation/#installation
Leave virtual environment with `$ deactivate`


# Installing a new package via pip
1. Install: `pip install peewee`
2. Save to requirements `pip freeze > requirements.txt`