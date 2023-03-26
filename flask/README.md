```console for linux
python3 -m venv venv
. venv/bin/activate

pip install Flask
pip install Flask-SQLAlchemy

export FLASK_APP=app.py
export FLASK_ENV=development
flask run
```

```console for windows
python3 -m venv env
. env/scripts/activate

pip install Flask
pip install Flask-SQLAlchemy

set FLASK_APP=app.py
set FLASK_ENV=development
flask run
```