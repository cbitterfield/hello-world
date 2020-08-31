==================
hello-world
==================


.. image:: https://img.shields.io/pypi/v/python_boilerplate.svg
        :target: https://pypi.python.org/pypi/python_boilerplate

.. image:: https://img.shields.io/travis/fgriberi/python_boilerplate.svg
        :target: https://travis-ci.org/fgriberi/python_boilerplate

.. image:: https://readthedocs.org/projects/python-boilerplate/badge/?version=latest
        :target: https://python-boilerplate.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

hello-world contains all the boilerplate you need to create a Python package.

Get Started!
--------
Here’s how to set up *hello-world* for local environment.

1- Clone the *hello-world* locally:

.. code-block:: console

    $ git clone ssh://git@github.com:cbitterfield/hello-world.git

2- Install your local copy into a *virtualenv*. Assuming you have *virtualenvwrapper* installed, this is how you set up the package for local development:

.. code-block:: console

    $ sudo make boostrap
    $ mkvirtualenv hello-world
    $ pip install -r requirements/dev.txt

3- How to enable/disable virtualenv

.. code-block:: console

    $ workon hello-world
    $ ...
    $ deactivate


Credits
-------

This package was generated using Yeoman_ and Cookiecutter_ projects.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _Yeoman: https://yeoman.io/learning/
