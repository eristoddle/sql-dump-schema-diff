This script was originally written to help me keep track of the evolution of Django models (hence the Python implementation). Before upgrading a staging server, I would compare the SQL dump from my development database (generated with `mysqldump -d` or with `python manage.py sql`) with the dump from my staging server.

Note that more sophisticated tools have been developed for this purpose, search for 'django schema evolution' on any search engine to find them.

This tool was developed as part of a [UML to Django conversion](http://code.google.com/p/uml-to-django/) project.