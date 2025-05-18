# new_app
new_app

below dependencies for Ubuntu/Linux systems.

1.apt install python3.12-venv

2.python3 -m venv venv

3.source venv/bin/activate

4.pip install Flask Flask-SQLAlchemy

5.pip install Flask Flask-Bcrypt

6.pip install Flask Flask-Mail

7.python3 app.py



--------------------------------------------

below for windows

first go to the directory where the app.py is present & run commands one by one below.

(venv) C:\Users\Sathish\Documents\Projects\new_app-main>python -m venv venv

(venv) C:\Users\Sathish\Documents\Projects\new_app-main>venv\Scripts\activate

(venv) C:\Users\Sathish\Documents\Projects\new_app-main>pip install flask
Collecting flask
  Using cached flask-3.1.1-py3-none-any.whl.metadata (3.0 kB)
Collecting blinker>=1.9.0 (from flask)
  Using cached blinker-1.9.0-py3-none-any.whl.metadata (1.6 kB)
Collecting click>=8.1.3 (from flask)
  Using cached click-8.2.0-py3-none-any.whl.metadata (2.5 kB)
Collecting itsdangerous>=2.2.0 (from flask)
  Using cached itsdangerous-2.2.0-py3-none-any.whl.metadata (1.9 kB)
Collecting jinja2>=3.1.2 (from flask)
  Using cached jinja2-3.1.6-py3-none-any.whl.metadata (2.9 kB)
Collecting markupsafe>=2.1.1 (from flask)
  Using cached MarkupSafe-3.0.2-cp311-cp311-win_amd64.whl.metadata (4.1 kB)
Collecting werkzeug>=3.1.0 (from flask)
  Using cached werkzeug-3.1.3-py3-none-any.whl.metadata (3.7 kB)
Collecting colorama (from click>=8.1.3->flask)
  Using cached colorama-0.4.6-py2.py3-none-any.whl.metadata (17 kB)
Using cached flask-3.1.1-py3-none-any.whl (103 kB)
Using cached blinker-1.9.0-py3-none-any.whl (8.5 kB)
Using cached click-8.2.0-py3-none-any.whl (102 kB)
Using cached itsdangerous-2.2.0-py3-none-any.whl (16 kB)
Using cached jinja2-3.1.6-py3-none-any.whl (134 kB)
Using cached MarkupSafe-3.0.2-cp311-cp311-win_amd64.whl (15 kB)
Using cached werkzeug-3.1.3-py3-none-any.whl (224 kB)
Using cached colorama-0.4.6-py2.py3-none-any.whl (25 kB)
Installing collected packages: markupsafe, itsdangerous, colorama, blinker, werkzeug, jinja2, click, flask
Successfully installed blinker-1.9.0 click-8.2.0 colorama-0.4.6 flask-3.1.1 itsdangerous-2.2.0 jinja2-3.1.6 markupsafe-3.0.2 werkzeug-3.1.3

[notice] A new release of pip is available: 24.0 -> 25.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip

(venv) C:\Users\Sathish\Documents\Projects\new_app-main>pip install Flask Flask-SQLAlchemy
Requirement already satisfied: Flask in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (3.1.1)
Collecting Flask-SQLAlchemy
  Using cached flask_sqlalchemy-3.1.1-py3-none-any.whl.metadata (3.4 kB)
Requirement already satisfied: blinker>=1.9.0 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (1.9.0)
Requirement already satisfied: click>=8.1.3 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (8.2.0)
Requirement already satisfied: itsdangerous>=2.2.0 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (2.2.0)
Requirement already satisfied: jinja2>=3.1.2 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (3.1.6)
Requirement already satisfied: markupsafe>=2.1.1 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (3.0.2)
Requirement already satisfied: werkzeug>=3.1.0 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (3.1.3)
Collecting sqlalchemy>=2.0.16 (from Flask-SQLAlchemy)
  Using cached sqlalchemy-2.0.41-cp311-cp311-win_amd64.whl.metadata (9.8 kB)
Requirement already satisfied: colorama in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from click>=8.1.3->Flask) (0.4.6)
Collecting greenlet>=1 (from sqlalchemy>=2.0.16->Flask-SQLAlchemy)
  Using cached greenlet-3.2.2-cp311-cp311-win_amd64.whl.metadata (4.2 kB)
Collecting typing-extensions>=4.6.0 (from sqlalchemy>=2.0.16->Flask-SQLAlchemy)
  Using cached typing_extensions-4.13.2-py3-none-any.whl.metadata (3.0 kB)
Using cached flask_sqlalchemy-3.1.1-py3-none-any.whl (25 kB)
Using cached sqlalchemy-2.0.41-cp311-cp311-win_amd64.whl (2.1 MB)
Using cached greenlet-3.2.2-cp311-cp311-win_amd64.whl (295 kB)
Using cached typing_extensions-4.13.2-py3-none-any.whl (45 kB)
Installing collected packages: typing-extensions, greenlet, sqlalchemy, Flask-SQLAlchemy
Successfully installed Flask-SQLAlchemy-3.1.1 greenlet-3.2.2 sqlalchemy-2.0.41 typing-extensions-4.13.2

[notice] A new release of pip is available: 24.0 -> 25.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip

(venv) C:\Users\Sathish\Documents\Projects\new_app-main>pip install Flask Flask-Bcrypt
Requirement already satisfied: Flask in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (3.1.1)
Collecting Flask-Bcrypt
  Using cached Flask_Bcrypt-1.0.1-py3-none-any.whl.metadata (2.6 kB)
Requirement already satisfied: blinker>=1.9.0 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (1.9.0)
Requirement already satisfied: click>=8.1.3 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (8.2.0)
Requirement already satisfied: itsdangerous>=2.2.0 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (2.2.0)
Requirement already satisfied: jinja2>=3.1.2 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (3.1.6)
Requirement already satisfied: markupsafe>=2.1.1 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (3.0.2)
Requirement already satisfied: werkzeug>=3.1.0 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (3.1.3)
Collecting bcrypt>=3.1.1 (from Flask-Bcrypt)
  Using cached bcrypt-4.3.0-cp39-abi3-win_amd64.whl.metadata (10 kB)
Requirement already satisfied: colorama in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from click>=8.1.3->Flask) (0.4.6)
Using cached Flask_Bcrypt-1.0.1-py3-none-any.whl (6.0 kB)
Using cached bcrypt-4.3.0-cp39-abi3-win_amd64.whl (152 kB)
Installing collected packages: bcrypt, Flask-Bcrypt
Successfully installed Flask-Bcrypt-1.0.1 bcrypt-4.3.0

[notice] A new release of pip is available: 24.0 -> 25.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip

(venv) C:\Users\Sathish\Documents\Projects\new_app-main>pip install Flask Flask-Mail
Requirement already satisfied: Flask in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (3.1.1)
Collecting Flask-Mail
  Downloading flask_mail-0.10.0-py3-none-any.whl.metadata (2.1 kB)
Requirement already satisfied: blinker>=1.9.0 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (1.9.0)
Requirement already satisfied: click>=8.1.3 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (8.2.0)
Requirement already satisfied: itsdangerous>=2.2.0 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (2.2.0)
Requirement already satisfied: jinja2>=3.1.2 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (3.1.6)
Requirement already satisfied: markupsafe>=2.1.1 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (3.0.2)
Requirement already satisfied: werkzeug>=3.1.0 in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from Flask) (3.1.3)
Requirement already satisfied: colorama in c:\users\sathish\documents\projects\new_app-main\venv\lib\site-packages (from click>=8.1.3->Flask) (0.4.6)
Downloading flask_mail-0.10.0-py3-none-any.whl (8.5 kB)
Installing collected packages: Flask-Mail
Successfully installed Flask-Mail-0.10.0

[notice] A new release of pip is available: 24.0 -> 25.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip

(venv) C:\Users\Sathish\Documents\Projects\new_app-main>python app.py
 * Serving Flask app 'app'
 * Debug mode: on
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:5000
 * Running on http://192.168.124.150:5000
Press CTRL+C to quit
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 959-575-390
127.0.0.1 - - [18/May/2025 11:12:55] "GET /login HTTP/1.1" 200 -
127.0.0.1 - - [18/May/2025 11:12:55] "GET /favicon.ico HTTP/1.1" 404 -
127.0.0.1 - - [18/May/2025 11:13:21] "POST /login HTTP/1.1" 200 -
