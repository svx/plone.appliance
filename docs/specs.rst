==============
Specifications 
==============
.. admonition:: Description

        Overview about the technical specifications of this VirtualBox Appliance.

.. contents:: :local:


.. toctree::
   :maxdepth: 2


Appliance Specifications
========================

+-----------------------+--------------------------------+
| CPU                   | 1                              |
+-----------------------+--------------------------------+
| RAM                   | 1024MB                         |
+-----------------------+--------------------------------+
| Operating System      | Ubuntu 14.04.2 -i386 Trusty LTS|
+-----------------------+--------------------------------+


Network
-------

Out of the box, the network in configured for NAT


+-----------------+---------------+
| Networking Mode | NAT           |
+-----------------+---------------+
| IP              | 10.0.3.15     |
+-----------------+---------------+

{HERE EXPLAIN WHY, reasons, security, bla}

However, dhcp is pre-configured on appliance, if for some reason you want to use dhcp [please ask you it-department fist], you can easily change that in the
netwok settings.
{here the manual}

- open virtualbox -> settings -> change to dhcp -> start vm again.

The appliance is build in the way,that you can now browse to the $IPOFTHEVM and see your plone setup.

The default network setup is nat, the default IP is 10.0.3.15.

{here pic of network in virtualbox gui}

Ports
~~~~~~

+-----------+--------------+
| Host      | Appliance    |
+-----------+--------------+
| 8080      | 8080         |
+-----------+--------------+  

Port 8080 of your Host is forwarded to port 8080 of the appliance.

Port 2222 of your Host OS forwarded to port 22 of the appliance.

{HERE PIC of network forwards}



User
----

Username: plone_user
sudo: yes
password: 123456plonedemo

.. warning:: Please do **not** use this appliance in production, is is not build for this!

Plone
-----
version: 5.0a2


.. warning:: Please do **not** use this appliance in production, is is not build for this!

