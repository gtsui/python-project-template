# Setup

## Virtual Env

To install python virtual environment:

`python3 -m venv venv`

To activate python virtual environment:

`source ./venv/bin/activate`

To deactivate python virtual environment:

`deactivate`

## Dependencies

To install required packages:

`(venv) pip install -r requirements.txt`

To update the requirements.txt file with new dependencies:

`(venv) pip3 freeze > requirements.txt`

## Jupyter

To open a Jupyter notebook run:

`(venv) jupyter notebook`

## Running Programs

To run the program `/src/main.py`, move above the application root folder and run:

`(venv) python3 -m [application_name].src.main`