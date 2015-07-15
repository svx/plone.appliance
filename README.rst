Plone VirtualBox Appliance
===========================

plone.virtualbox.appliance is an easy way to evaluate `Plone <https://plone.org>`_.


`VirtualBox <https://www.virtualbox.org>`_ is the only needed dependency. 

** This appliance is not suited for production use** 

For Plone in production please refer to the `official <http://docs.plone.org>`_ documentation.

Features
--------

- Be awesome
- Make things fancier
- Works out of the box, but can also be customized.
  After installation, you will find a new item in your site control panel where to set various options.


Examples
--------

This add-on can be seen in action at the following sites:
- http://fancysite.com
- http://fluffystuff.org


Documentation
-------------

Full documentation for end users can be found in the "docs" folder.
It is also available online at http://docs.plone.org/foo/bar


Translations
------------

This product has been translated into

- Klingon (thanks, K'Plai)


Installation
------------

Install collective.fancystuff by adding it to your buildout:

   [buildout]

    ...

    eggs =
        collective.fancystuff


and then running "bin/buildout"



Contribute
----------

- Issue Tracker: github.com/collective/collective.fancystuff/issues
- Source Code: github.com/collective/collective.fancystuff
- Documentation: docs.plone.org/foo/bar

Support
-------

If you are having issues, please let us know.
We have a mailing list located at: project@example.com

License
-------

The project is licensed under the GPLv2.

Tracking changes

Feature-level changes to code are tracked inside CHANGES.rst. The title of the CHANGES.rst file should be Changelog. Example:

Changelog
=========

1.0.0-dev (Unreleased)
----------------------

- Added feature Z.
  [github_userid1]

- Removed Y.
  [github_userid2]


1.0.0-alpha.1 (yyyy-mm-dd)
--------------------------

- Fixed Bug X.
  [github_userid1]

Add an entry every time you add/remove a feature, fix a bug, etc. on top of the current development changes block.
Table of Contents for your documentation

Make sure all .rst files are referenced with a Table of Contents directive, like this example:

.. toctree::
   :maxdepth: 2

   quickstart
   working_examples
   absolutely_all_options_explained
   how_to_contribute

(note: the files themselves will have an extention of .rst, but you don't specify that extension in the toctree directive)

