# Django Q on Digital Ocean App Platform

The intent of this repo is to deploy successfully Django Q workers on DO App Platform.

## Run Locally

- Install requirements
```
pip install -r requirements.txt
```

- Apply Django Q required migrations
```
python manage.py migrate
```

- Run Django Q
```
python manage.py qcluster
```
