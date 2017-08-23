FLASK
=====

Flask Is a web application server.
When we think about python web application what comes to our mind is Django. However for beginners the simplest framework to learn would be flask.

VIRTUAL ENVIRONMENT
-------------------

`virtualenv` is a virtual Python environment builder. It helps a user to create multiple Python environments side-by-side. Thereby, it can avoid compatibility issues between the different versions of the libraries.

* To install on Linux `Sudo apt-get install virtualenv`
* On Mac `pip install virtualenv`
* To create virtual environment `virtualenv venv`
* To activate
`source venv/bin/activate`

Installing Flask  
----------------

Flask can be installed with pip package manager
* `pip install flask`

Creating basic Hello World
--------------------------
* create an app.py
* import flask
```
from flask import Flask
app = Flask(__name__)
```
* define route for / to return hello world
```
@app.route("/")
def main():
    return "Hello World!"
```
* add main program to run the app
```
if __name__ == "__main__":
    app.run()
```

* run the app
`python app.py`

