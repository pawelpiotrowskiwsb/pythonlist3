# pythonlist3
 ```
  # tworzymy środowisko dla pythona
  > python -m venv .venv

  # aktywujemy środowisko
  > source .venv/Scripts/activate
  > pip install -r requirements.txt

  # zobacz czy jest zainstalowanie
  > pip list
  ```

- Uruchamianie applikacji:

  ```
  > PYTHONPATH=. FLASK_APP=hello_world flask run
  ```

- Aktywacja środowiska hermetycznego.

  ```
  # deaktywacja
  > deactivate
  ```

  ```
  ...

  # aktywacja 
  > source .venv/bin/activate
  ```
