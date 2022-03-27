# pythonlist3
1. tworzymy ścieżke do naszego foldera.
	mkdir FlaskApp
	cd FlaskApp

2. teraz zaczynamy używać pythona.
	py -3 -m venv venv

3. aktywujemy skrypty.
	venv\Scripts\activate
4. instalujemy Flask.
	pip install Flask
5.tworzymy plik helloworld.py w którym zapisany będzie kod </BR>
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return "Hello, World!"
6. Deklarujemy hello world jako flask app.
	set FLASK_APP=hellowrold.py </br>
7. uruchamiamy flask.
	flask run
8. kopiujemy adres i wklejamy w przeglądarke
