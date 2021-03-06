Django Pipeline Compass
=======================

`Compass`_ compiler for django-pipeline using the original Ruby Gem.

Requirements
------------

* Compass: ``gem install compass``

Installation
------------

.. code-block:: bash

    # from PyPi
    $ pip install django-pipeline-compass-rubygem

    # from GitHub
    $ pip install git+https://github.com/mila-labs/django-pipeline-compass-rubygem.git

Usage
-----

.. code-block:: python

    # settings.py

    PIPELINE_COMPASS_BINARY = '/usr/local/bin/compass'   # default: '/usr/bin/env compass'
    PIPELINE_COMPASS_ARGUMENTS = '-c path/to/config.rb'  # default: ''

    PIPELINE_COMPILERS = (
      'pipeline_compass.compass.CompassCompiler',
    )

.. _Compass: http://compass-style.org/
