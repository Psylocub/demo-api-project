# API project of food recipes

## Setup

**Setup .ENV file**
```
$ Rename .env.sample to .env and fill all data
```

**Run application**

```
$ docker-compose up
```

**Run tests**

```
$ docker-compose run --rm app sh -c "python manage.py test"
```

## API documentation

* Swagger schema: [api/schema/](http://127.0.0.1:8000/api/schema/)
* Docs: [api/docs/](http://127.0.0.1:8000/api/docs/)