.. image:: https://travis-ci.org/boundlessgeo/qgis-lessons-plugin.svg?branch=master
    :target: https://travis-ci.org/boundlessgeo/qgis-lessons-plugin

Lessons
=======

A plugin for QGIS to create step-by-step lessons and tutorials.

Contribute
----------

If you wish to contribute patches you can `fork the project <https://help.github.com/forking/>`_, make your changes, commit to your repository, and then `issue a pull request <http://help.github.com/pull-requests/>`_. The development team can then review your contribution and commit it upstream as appropriate.

Documentation
-------------

The plugin is documented `here <https://connect.boundlessgeo.com/docs/desktop/plugins/lessons/>`_.

Cloning this repository
-----------------------

This repository uses external repositories as submodules. Therefore in order to include the external repositories during cloning you should use the *--recursive* option:

git clone --recursive http://github.com/boundlessgeo/qgis-lessons-plugin.git

Also, to update the submodules whenever there are changes in the remote repositories one should do:

git submodule update --remote


Sample lessons
---------------

By default, the  package task will add lessons from the desktop-lessons repository. To avoid it, use the ``--nolessons`` modifier


