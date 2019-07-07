# simple wsgi implementation

development

```
FLASK_APP=main.py flask run
```

production

```
gunicorn -w 4 -b 127.0.0.1:5000 wsgi:app
```