# Python Blog using Flask

This is a blog, written in Python, that uses the Flask web framework.

## Installation and Setup

1. Create a Python 3 virtual environment

    `python3 -m venv venv`

2. Activate the virtual environment

    `source venv/bin/activate`

3. Install Python packages

    `pip install -r requirements.txt`

4. Create the required database and tables by performing the DB migrations:

    `flask db upgrade`

    > Note: this will create an app.db file on your local machine, and use sqlite as a database engine.

5. Start a local flask server

    `flask run`

7. Launch your browser, and open the url from the previous step
