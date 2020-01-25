# Chat application implementation using Django channels

## Requirements

> python 3.5

initialize virtual environment

```
virtualenv venv
```

activate virtual environment

```
source venv/bin/activate
```

install dependencies

```
pip install -r requirements.txt
```

run redis in a docker container

```
docker run -p 6379:6379 -d redis:2.8
```

migrate the database

```
python src/manage.py migrate
```

run tests

```
python src/manage.py test chat.tests
```

run the server

```
python src/manage.py runserver
```
