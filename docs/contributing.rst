=============
Contributing
=============

.. admonition:: Contriburing to the documentation

	Please feel free help improving this documentation, you can contribute in different ways, like open
	`tickets <https://github.com/svx/plone.appliance/issues/>`_ or sending pull requests.

If you want to build the documentation locally, please see below.

Dependencies
------------

Make sure to have the follwoing dependencies installed:

- python2.7
- virtualenv

Install
-------

Clone this repository:

.. code-block:: bash

	git clone https://github.com/svx/plone.appliance


Create virtualenv and activate it:

.. code-block:: bash

	$ cd plone.virtualbox.appliance
	$ virtualenv --python=python2.7 .
	$ source bin/activate

Install requirements:

.. code-block:: bash

	$ pip install -r requirements.txt

Building
--------

.. code-block:: bash

	$ cd plone.virtualbox.appliance/docs
	$ make install

Browsing
--------

Point your browser to file:///$YOURPATH/plone.appliance/docs/_build/html/index.html#

.. note:: Replace *YOURPATH* with your local path, for example */home/jandoe/*
