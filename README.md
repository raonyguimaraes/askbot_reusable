askbot_reusable
===============

Askbot integrated with Django 1.5 to be used as reusable Django application.

Installation
============

    mkvirtualenv askbot
    git clone git@github.com:raonyguimaraes/askbot_reusable.git
    cd askbot_reusable
    pip install -r requirements.txt
    python manage.py collectstatic
    python manage.py syncdb
    python manage.py runserver
    