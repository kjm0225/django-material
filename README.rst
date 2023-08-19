===============
Django Material
===============

Material design for Django.


IN ORDER TO REDUCE MAINTENANCE COST, THE PACKAGE FUNCTIONALITY HAS BEEN MOVED INTO THE django-viewflow

PLEASE, CONSIDE TO UPGRADE

$ pip install django-viewflow>=2.0.0b1


Overview
========

- Forms - New way to render django forms

  * Strong python/html code separation
  * Easy redefinition of particular fields rendering
  * Complex form layout support

- Frontend - Quick starter template for modular admin-line applications development

.. image:: .screen.png
   :width: 400px


Demo
====

http://forms.viewflow.io/

To checkout and run open source demo version locally, you need to have
`git <https://git-scm.com/>`_ and `tox
<https://tox.readthedocs.io/en/latest/>`_ tools installed.

.. code:: bash

    git clone https://github.com/viewflow/django-material.git
    cd django-material

    TOXENV=py36-dj111 tox -- python manage.py migrate --settings=demo.settings
    TOXENV=py36-dj111 tox -- python manage.py loaddata demo/fixtures/* --settings=demo.settings
    TOXENV=py36-dj111 tox -- python manage.py runserver --settings=demo.settings

Then you can go to http://127.0.0.1:8000/integration/ and login with
`admin:admin` username and password to the demo site.

