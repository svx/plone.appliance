=====
Setup
=====
.. admonition:: Description

        Overview about the setup of this VirtualBox Appliance.

.. contents:: :local:


.. toctree::
   :maxdepth: 2


Appliance Setup
===============

Specs
-----
CPU: 1

RAM: 1024MB

Operating System
----------------

Ubuntu 14.04.2 -i386 [32] - Trusty T LTS

Network
-------

The default network setup is nat, the default IP is {HEREIP}.

{here pic of network in virtualbox gui}

Ports
~~~~~~
Port: {Host}:{Client}
Port 8080 of your Host is forwarded to port 8080 of the appliance.

Port 2222 of your Host OS forwarded to port 22 of the appliance.

{HERE PIC of network forwards}

However, dhcp is pre-configured on appliance, if for some reason you want to use dhcp [please ask you it-department fist], you can easily change that in the
netwok settings.
{here the manual}

- open virtualbox -> settings -> change to dhcp -> start vm again.

The appliance is build in the way,that you can now browse to the $IPOFTHEVM and see your plone setup.

User
----

Username: plone_user
sudo: yes
password: 123456plonedemo

.. warning:: Please do **not** use this appliance in production, is is not build for this!

Plone
-----
version: 5.0a2
user: admin
password: plone

.. warning:: Please do **not** use this appliance in production, is is not build for this!

- more ?

- feedback/suggestions ?
