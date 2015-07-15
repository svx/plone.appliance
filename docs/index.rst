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
   :titlesonly: 

   specs
   contributing


Introduction
============

To make it easier for anyone to review or evaluate `Plone <https://plone.com>`_, we provide this **VirtualBox Plone Appliance**.

It is a self-contained appliance that will run independent from your current operating system.
So you don't have to go to separate install steps. 

Do note that this is **not** meant for production environments.

The only application you need is `Virtualbox <https://www.virtualbox.org>`_.

Preparation
===========

Please make sure that you have `Virtualbox <https://www.virtualbox.org>`_ installed.

Mac OS X
---------

If you do not have `Virtualbox <https://www.virtualbox.org>`_ installed, please `download <https://www.virtualbox.org/wiki/Downloads>`_ VirtualBox for OS X hosts.

.. thumbnail:: _static/vbox_show_osx.png
   :width: 697px
   :height: 392px
   :align: center


Click on the underlined link to download it. After the download is finished open the downloaded file. Now follow the steps to install VirtualBox to your machine.

.. todo:: more pictues about installation

Windows
-------

If you do not have `Virtualbox <https://www.virtualbox.org>`_ installed, please `download <https://www.virtualbox.org/wiki/Downloads>`_ VirtualBox for Windows hosts.

Once downloaded, double-click on the installer which will guide you through the installation. Depending on your version of Windows, you will be asked for permission to install non-Windows signed drivers, which are needed to complete the installation. 

Ubuntu
------

If you do not have `Virtualbox <https://www.virtualbox.org>`_ installed, please open the software center, in Unity, Ubuntu Software Center should be a default item in the launcher.

Alternatively, search for “software” in the Dash search field. 

Now search in the right top corner for *virtualbox*.

.. thumbnail:: _static/ubuntu_software_center.png
   :width: 697px
   :height: 392px
   :align: center



.. todo:: more and 'fresh' pics about installation

and install it, if you wish to install it via command-line please do:

.. code-block:: bash

    $ sudo apt-get install virtualbox


Downloading Appliance
=====================

Browse to `dist.plone.org/vm <http://dist.tiramisu.solutions/virtualbox/>`_ and click on plone5.0-ubuntu-appliance to download it.

Importing Appliance
===================

After the download is finished you can import it into VirtualBox. In order to do that, first you have to *unzip* the file you just downloaded.
Go into your download folder [or to the folder where you saved the file], *right* click with the moouse on it and choose *unzio*.

After that is done, please start VirtualBox on your machine. If all went well you will see something what will look similar like the picture.

.. note:: Depending if you use Windows, Mac or Linux it is possible that it will look slightly different.

.. thumbnail:: _static/virtualbox_start_screen.png
   :width: 697px
   :height: 392px
   :align: center

- Lets import the image, click on **File** -> **Import Appliance**
- Click **Open appliance** and navigate to the already downloaded and unzipped image
- Click **open** again
- Click **Next**
- Click **Import**
- Wait till import is done


Starting
========

 - choose the appliance image, click on start and hopefully the fresh imported image will boot.

All about Starting

.. todo:: here screens

- Wait till you see a login screen, that means the Appliance is booted and ready.

Plone
=====

Open your browser and enter: http://localhost:8080/Plone



