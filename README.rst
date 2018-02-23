==========
systeminfo
==========


.. image:: https://img.shields.io/pypi/v/systeminfo.svg
        :target: https://pypi.python.org/pypi/systeminfo

.. image:: https://img.shields.io/travis/harshrpg/systeminfo.svg
        :target: https://travis-ci.org/harshrpg/systeminfo

.. image:: https://readthedocs.org/projects/systeminfo/badge/?version=latest
        :target: https://systeminfo.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status




This project provides us with the details about the system it is installed on. Made on CookieCutter


* Free software: MIT license
* Documentation: https://systeminfo.readthedocs.io.


Features
--------

This is a private package that gives the user the information of the operating system it is installed in. 


Installation
-------------

To use this application simply follow the following steps:

1. Install ``systeminfo`` by executing the following command::
        
        pip install git+https://github.com/harshrpg/systeminfo.git

2. Enter python terminal by executing ``python``
3. Use this package by importing the module::
	
	>> import sysinfo

4. Run the command::

	>> sysinfo.get_platform_info()

Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
