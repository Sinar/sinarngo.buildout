======================
Sinar NGO Buildout
======================

A Plone_ buildout that consists of Plone and supporting packages, that
are useful for setting up and hosting a web Content Management System
for NGO sites.

This  buildout configuration  automatically buildis development
and deployment versions of this platform.


Debian
======

Dependencies
------------

Pillow

::
    libjpeg-dev
    libfreetype6-dev
    zlib1g-dev
    liblcms1-dev
    git i
    python-dev 
    libxslt-dev 
    libxml2-dev 
    libjpeg8-dev 
    libpng12-dev
    zlib1g-dev

Setup for development
---------------------

1. virtualenv --no-setuptools buildout-env
2. buildout-env/bin/python bootstrap.py
3. bin/buildout -vv

To run instance:

1. bin/instance fg
2. default password admin:admin
3. create Plone site

Sites currently on this platform
================================

* `Sinar Project`_

Credits
=======

Development of this platform was possible due funnding support from:

 * IDRC <www.idrc.ca> through e-DirAP project <digitalreview.asia>
 * InterNews <www.internews.org>
 * SEATTI <www.seatti.org>

.. _Plone http://plone.org
.. _`Sinar Project` http://sinarproject.org
