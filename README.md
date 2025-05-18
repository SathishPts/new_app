# new_app
new_app

**below dependencies for Ubuntu/Linux systems.**

1.apt install python3.12-venv

2.python3 -m venv venv

3.source venv/bin/activate

4.pip install Flask Flask-SQLAlchemy

5.pip install Flask Flask-Bcrypt

6.pip install Flask Flask-Mail

7.python3 app.py



--------------------------------------------

**below for windows**

first download or clone the repository to local

then go to the directory where the app.py is present & run commands one by one below.

1.for best result install python 3.12

2.python -m venv venv

3.source venv/bin/activate

4.pip install -r requirments.txt

7.python app.py

---------------------------------------------

To change the port of the server 
change the last line in app.py file with whatever port you want

if __name__ == '__main__':
    app.run(debug=True, host='0.0.0.0', port=5454)

