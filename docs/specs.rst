==============
Specifications
==============
.. admonition:: Description

        Overview about the technical specifications of this VirtualBox Appliance.

.. contents:: :local:

.. _os-reference-label:

Supported Operating Systems
===========================

:term: 'test'

and there we go :term:`Plone` bla bla bla

This Appliance is tested on following Operating Systems:

+---------------+----------------------+
| Ubuntu        | 14.04, 15.04         |
+---------------+----------------------+
| Mac OS X      | Yosemite             |
+---------------+----------------------+
| Windows       | 8                    |
+---------------+----------------------+
| Debian        | 8                    |
+---------------+----------------------+
| Arch Linux    | build: 2015.07.01    |
+---------------+----------------------+


Supported VirtualBox Versions
==============================

This Appliance is tested with:

+-----------+
| 4.3.28    |
+-----------+
| 4.3.30    |
+-----------+
| 5.0       |
+-----------+

Appliance Specifications
========================

*Beta 2*

+-----------------------+---------------------------------+
| CPU                   | 1                               |
+-----------------------+---------------------------------+
| RAM                   | 1024MB                          |
+-----------------------+---------------------------------+
| Operating System      | Ubuntu 14.04.2 - 386 Trusty LTS |
+-----------------------+---------------------------------+

*Beta 3*

+-----------------------+---------------------------------+
| CPU                   | 1                               |
+-----------------------+---------------------------------+
| RAM                   | 1024MB                          |
+-----------------------+---------------------------------+
| Operating System      | Debian 8.1                      |
+-----------------------+---------------------------------+

Network
-------

Out of the box, the network in configured for NAT

*Beta 2*

+-----------------+---------------+
| Networking Mode | NAT           |
+-----------------+---------------+
| IP              | 10.0.3.15     |
+-----------------+---------------+

*Beta 3*

+-----------------+---------------+
| Networking Mode | NAT           |
+-----------------+---------------+
| IP              | 10.0.2.15     |
+-----------------+---------------+


For preventing possible interference with your network, the appliance is using NAT as default configured network mode.

This means the appliance is only reachable from the host machine, meaning the machine where you using VirtualBox on.

.. thumbnail:: _static/virtualbox_nat.png
   :width: 697px
   :height: 392px
   :align: center


However, dhcp is pre-configured on the appliance, if for some reason, you want to use dhcp, you can easily change that in the network settings.

.. warning:: Before you do that, please consult your IT-department first !


Open virtualbox -> settings -> change to dhcp -> start vm again.

The appliance is build in the way,that you can now browse to the $IPOFTHEVM and see your plone setup.


.. thumbnail:: _static/virtualbox_dhcp.png
   :width: 697px
   :height: 392px
   :align: center

Ports
~~~~~~

+-----------+--------------+
| Host      | Appliance    |
+-----------+--------------+
| 8080      | 8080         |
+-----------+--------------+
| 2222      | 22           |
+-----------+--------------+


Port 8080 of your Host is forwarded to port 8080 of the appliance.

Port 2222 of your Host is forwarded to port 22 of the appliance

.. thumbnail:: _static/virtualbox_port_fw.png
   :width: 697px
   :height: 392px
   :align: center




User
----

The user under which the setup is done on, you can also use these credentials to login via the command-line or via the command-line login prompt from VirtualBox.

*Beta 2*

+------------+-----------------+
| username   | plone_user      |
+------------+-----------------+
| password   | 123456plonedemo |
+------------+-----------------+
| sudo       | yes             |
+------------+-----------------+

*Beta 3*

+------------+-----------------+
| username   | ploneuser       |
+------------+-----------------+
| password   | plonedemo       |
+------------+-----------------+
| sudo       | no              |
+------------+-----------------+
| root       | PloneRoot       |
+------------+-----------------+


Examples:

Login via command-line to the appliance on the default NAT:

.. code-block:: bash

	$ ssh plone_user@10.0.3.15

Login via the VirtualBox server/command-line prompt:

.. thumbnail:: _static/vbox_login_cmd.png
   :width: 697px
   :height: 392px
   :align: center



Plone
-----

*Beta 2*

+--------------+-----------------------------------+
| Version      | 5.0b2                             |
+--------------+-----------------------------------+
| Install path | /home/plone_user/Plone/zinstance  |
+--------------+-----------------------------------+

*Beta 3*

+--------------+-----------------------------------+
| Version      | 5.0b3                             |
+--------------+-----------------------------------+
| Install path | /home/ploneuser/Plone/zinstance   |
+--------------+-----------------------------------+

.. warning:: Please do **not** use this appliance in production, is is not build for this!

