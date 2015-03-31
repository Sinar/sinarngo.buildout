Plone buildout for Sinar Project's shared Plone services.

Steps and dependencies to install on Ubuntu
===========================================

Dependencies:

git python-dev libxslt-dev libxml2-dev libjpeg8-dev libpng12-dev
zlib1g-dev

Setup for development
---------------------

1. virtualenv --no-setuptools buildout-env
2. buildout-env/bin/python bootstrap.py
3. bin/buildout -vv



