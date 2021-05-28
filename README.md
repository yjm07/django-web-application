# django-web-application
<b>Terminology description</b>
- <b>Models</b>: interface with database. Python ORM for Django. Map Python class and DB table 1:1.
    1. Write Model class
    2. Model class -> migration files: 'makemigrations'
    3. Apply to DB: 'migrate' \
    cf) When DB is outside of Django: 'inspectdb'
- <b>Views</b>: function or class for HTTP requests. 1:1 view and request.
- <b>Templates</b>: rendering engine to deal with complicated string combination.
- <b>ORM(Object Relational Mapping)</b>: map object with SQL so that user can run DB easily without using SQL instructions. \
Ex) SQLAlchemy, MongoEngine, hot-redis
- <b>Form</b>: can input data to database and check validations of inputs.
