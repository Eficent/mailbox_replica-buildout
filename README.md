Mailbox Replica Buildout
========================

* You must install the following packages with apt-get:
- libffi-dev

* Clone this repo.

* Create a virtual environment inside the cloned code:
virtualenv sandbox --no-setuptools

* > source /sandbox/bin/activate
* > python bootstrap.py
* > bin/buildout

Execute with bin/start_odoo7 --db_user=< > --db_password=<> --db_host localhost

