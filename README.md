# WebApplication - Django(Python)
A web aplication (backend and frontend) useful for storage information about actors, theaters and cities. It offers CRUD operations (Create, Read, Update and Delete - the four basic operations) and is using  MySQL database service.

If you want to run the server you must download and import the empty database!
Steps to run the server:
- open database.py and modify the fields: host, user, password, database (name of the database in your mysql server)
- open command prompt/shell and navigate to the project folder
- run "python manage.py livereload" and "python manage.py runserver" commands
- start a web browser and navigate to http://127.0.0.1:8000/ (localhost)
Python packages:
- mysql connector
- django
- tabulate
- pathlib
- sys

Website offers CRUD functions (Create, Read, Update, Delete). 
The database contains 3 tables: Cities, Theaters and Actors. 
See the database diagram for more infos about foreign keys.

Create: if you add a new theater/actor you can select which city/theater you want.
Read: can sort the table by a field ascending/descending.
Update: can chose if you want to move a theater/actor to another city/theater.
Delete: choose the elements you want to delete.
