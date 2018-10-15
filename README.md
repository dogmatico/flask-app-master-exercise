# Foundations of Data Science - Exercise SAS(2)
The scope of the exercise is:

* Copy and paste the Flask App,
* Add the edit product controller,
* Deploy on Heroku.

## Development server
To run the development instance, execute

```bash
python manage.py runserver
```

The instance requires the following environment variables:
* MONGO_DBNAME
* MONGO_URI
* SECRET_KEY
* SESSION_PROTECTION

A template to export the variables is provided in `env.template`. Complete the template, rename to `env` and run

```bash
./env python manage.py runserver
```

## Heroku instance
An instance of the APP is deployed in https://flask-master-ds-clorenzo.herokuapp.com/

The credentials are the same that the given in the Jupyter notebook.