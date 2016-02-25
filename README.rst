=====
Kordebooking
=====

Booking app for korde cms. Built on django rest framework. Only defines endpoints and models.

Detailed documentation is in the "docs" directory.

Quick start
-----------

Installation

pip install git+git://github.com/RubenSchmidt/kordebooking.git


1. Add "kordecms" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'kordebooking',
    ]

2. Include the polls URLconf in your project urls.py like this::

    url(r'^cms/', include('kordebooking.urls')),

3. Run `python manage.py migrate` to create the kordecms models.

