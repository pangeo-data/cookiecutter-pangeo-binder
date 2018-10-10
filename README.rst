======================
Cookiecutter PyPackage
======================

.. image:: https://travis-ci.org/pangeo-data/cookiecutter-pangeo-binder.svg?branch=master
    :target: https://travis-ci.org/pangeo-data/cookiecutter-pangeo-binder     

Cookiecutter_ template for a Pangeo-Binder Repository.

* GitHub repo: https://github.com/pangeo-data/cookiecutter-pangeo-binder/
* License: BSD

Features
--------

* Automatically sets up binder and dask configurations
* Prepopulates environment with commonly used Pangeo/Python packages
* Example notebook with first steps toward deploying a dask cluster on kubernetes

.. _Cookiecutter: https://github.com/audreyr/cookiecutter

Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/pangeo-data/cookiecutter-pangeo-binder.git

Then:

* Create a repo and put it on GitHub.
* Add some more notebooks and configure your software environment.
* Use binder.pangeo.io to launch your repo.
* Share with the Pangeo Community
