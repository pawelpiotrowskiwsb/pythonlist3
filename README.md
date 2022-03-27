# pythonlist3
1. tworzymy ścieżke do naszego foldera.
	mkdir FlaskApp
	cd FlaskApp

2. teraz zaczynamy używać pythona.
	py -3 -m venv venv

3. aktywujemy skrypty.
	venv\Scripts\activate
4. instalujemy Flask.</BR>
	pip install Flask</BR>
5.tworzymy plik helloworld.py w którym zapisany będzie kod </BR>
from flask import Flask</BR>

app = Flask(__name__)</BR>

@app.route("/")</BR>
def hello_world():</BR>
    return "Hello, World!"</BR>
6. Deklarujemy hello world jako flask app.
	set FLASK_APP=hellowrold.py </br>
7. uruchamiamy flask.</BR>
	flask run</BR>
8. kopiujemy adres i wklejamy w przeglądarke
