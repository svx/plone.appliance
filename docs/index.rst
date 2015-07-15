==========================
Plone VirtualBox Appliance
==========================

.. admonition:: Description

        The VirtualBox Appliance is meant for *quick reviews* of `Plone <https://plone.com>`_.
        You do not have to be a developer or have to know `vagrant <https://www.vagrantup.com>`_ or other tools.
        If you have `VirtualBox <https://www.virtualbox.org>`_ already installed, you just can download, import
        and start the appliance.

        This is tested with Ubuntu, Mac OS and Windows

.. todo:: Add specific versions where we tested on, like Ubuntu 14.04, Windows 8 ?

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



Downloading Appliance
=====================

Browse to `dist.plone.org/vm <http://dist.tiramisu.solutions/virtualbox/>`_ and click on plone5.0-ubuntu-appliance to download it.

Importing Appliance
===================

After the download is finished you can import it into VirtualBox. 


After that is done, please start VirtualBox on your machine. If all went well you will see something what will look similar like the picture.

.. note:: Depending if you use Windows, Mac or Linux it is possible that it will look slightly different.

.. thumbnail:: _static/virtualbox_start_screen.png
   :width: 697px
   :height: 392px
   :align: center


Starting
========

 - choose the appliance image, click on start and hopefully the fresh imported image will boot.

All about Starting

.. todo:: here screens

- Wait till you see a login screen, that means the Appliance is booted and ready.

Plone
=====

Open your browser and enter: http://localhost:8080/Plone

If you want to login to http://localhost:8080/Plone/login please use this credentials: 

+----------+-------+
| username | admin |
+----------+-------+
| password | plone |
+----------+-------+


