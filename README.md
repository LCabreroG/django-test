# Django test

Steps when you apply changes to models:
* Change your models (in models.py).
* Run `python3 manage.py makemigrations` to create migrations for those changes
* Run `python3 manage.py migrate` to apply those changes to the database.

Testing the code:
* Include test in tests.py
* Run `python3 manage.py test polls`