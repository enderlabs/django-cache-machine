=============
Cache Machine
=============

Cache Machine provides automatic caching and invalidation for Django models
through the ORM.

For full docs, see https://cache-machine.readthedocs.org/en/latest/.

.. image:: https://travis-ci.org/django-cache-machine/django-cache-machine.svg?branch=master
  :target: https://travis-ci.org/django-cache-machine/django-cache-machine

.. image:: https://coveralls.io/repos/django-cache-machine/django-cache-machine/badge.svg?branch=master
  :target: https://coveralls.io/r/django-cache-machine/django-cache-machine?branch=master


Requirements
------------

Cache Machine currently works with:

* Django 4.2, 5.0, 5.1, and 5.2
* Python 3.10, 3.11, and 3.12

The last version to support Python 3.9 and Django 4.0/4.1 is ``django-cache-machine==1.2.0``.
The last version to support Python 2.7 and Django 1.11 is ``django-cache-machine==1.1.0``.

Installation
------------

Get it from `pypi <http://pypi.python.org/pypi/django-cache-machine>`_::

    pip install django-cache-machine


Running Tests
-------------

Get it from `github <http://github.com/django-cache-machine/django-cache-machine>`_::

    git clone git://github.com/django-cache-machine/django-cache-machine.git
    cd django-cache-machine
    pip install -r dev-requirements.txt
    python run_tests.py
