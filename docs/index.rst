==========================
Plone VirtualBox Appliance
==========================

.. admonition:: Description

        The VirtualBox Appliance is meant for *quick reviews* of `Plone <https://plone.com>`_.
        You do not have to be a developer or have to know `vagrant <https://www.vagrantup.com>`_ or other tools.
        If you have `VirtualBox <https://www.virtualbox.org>`_ already installed, you just can download, import
        and start the appliance.

        :ref:`os-reference-label`


.. toctree::
   :hidden:

   setup/index
   specs
   contributing

Introduction
============

To make it easier for anyone to review or evaluate `Plone <https://plone.com>`_, we provide this **VirtualBox Plone Appliance**.

It is a self-contained appliance that will run independent from your current operating system.
So you don't have to go to separate install steps.

.. note:: This appliance is **not** meant for production environments.

The only application you need is `Virtualbox <https://www.virtualbox.org>`_.


Downloading the Appliance
=========================

*Beta2*

Browse to `dist.plone.org/vm <http://dist.tiramisu.solutions/virtualbox/>`_ and click on plone5.0-ubuntu-appliance to download it.

*Beta 3*

Browse to `dist.plone.org/vm <http://dist.tiramisu.solutions/virtualbox/>`_ and click on plone5b3_build250715.ova to download it.

Importing the Appliance
=======================

Please click on the link according to your Operating System

:doc:`Importing into Virtualbox on Ubuntu <setup/ubuntu>`

:doc:`Importing into Virtualbox on Mac OS X <setup/osx>`

:doc:`Importing into Virtualbox on Windows <setup/windows>` 

.. _starting-reference-label:

Starting the Appliance
======================

Choose the Appliance, click on start and hopefully the fresh imported image will boot.

.. thumbnail:: _static/starting_appliance_vbox.png
   :width: 697px
   :height: 392px
   :align: center

.. note:: The name of the Appliance may differ, depending on the version


Wait till you see a login screen, that means the Appliance is booted and ready.

Plone
=====

Open your browser and enter: http://localhost:8080/Plone

If you want to login to http://localhost:8080/Plone/login please use these credentials:

*Beta 2*

+----------+-------+
| username | admin |
+----------+-------+
| password | plone |
+----------+-------+

*Beta 3*

+----------+-------+
| username | admin |
+----------+-------+
| password | admin |
+----------+-------+
