Para executar este teste, será necessário ter instalado o python3, o pip para o python3 e o venv para o python3

https://flask.palletsprojects.com/en/1.1.x/installation/#installation

entrar neste diretório
usar
$ python3 -m venv venv

depois 

$ . venv/bin/activate

a partir daí

$ pip install Flask

$ export FLASK_APP=app.py
$ flask run

inspirado em https://dev.to/paurakhsharma/flask-rest-api-part-2-better-structure-with-blueprint-and-flask-restful-2n93

https://realpython.com/invalid-syntax-python/
https://pythonforbiologists.com/29-common-beginner-errors-on-one-page
https://docs.python.org/3/tutorial/classes.html

FLASK_APP = app.py
FLASK_ENV = development
FLASK_DEBUG = 0
In folder ~/code-example/py_01
~/code-example/py_01/venv/bin/python -m flask run
