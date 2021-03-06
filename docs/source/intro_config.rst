Configuration File
==================

.. contents:: Topics

Below is full coverage of each of the sections of the values available in :code1.5:`linchpin.conf <linchpin/linchpin.conf>`.

Getting the most current configuration
--------------------------------------

If you are installing LinchPin from a package manager (pip or RPM), the latest linchpin.conf is already included in the library.

An example :code1.5:`linchpin.conf <linchpin/linchpin.conf>` is available on Github.

For in-depth details of all the options, see the :doc:`Configuration Reference <configuration>` document.

Environmental Variables
-----------------------

LinchPin allows configuration adjustments via environment variables in some cases. If these environment variables are set, they will take precedence over any settings in the configuration file.

A full listing of available environment variables, see the :doc:`Configuration Reference <configuration>` document.

Command Line Options
--------------------

Some configuration options are also present in the command line. Settings passed via the command line will override those passed through the configuration file and the environment.

The full list of options is covered in the :doc:`cli` document.

Values by Section
-----------------

The configuration file is broken into sections. Each section controls a specific functionality in LinchPin.

General Defaults
````````````````
.. include:: conf/defaults.rst
.. include:: conf/lp.rst

Extra Vars
``````````
.. include:: conf/evars.rst

Initialization Settings
```````````````````````
.. include:: conf/init.rst

Logger Settings
```````````````
.. include:: conf/logger.rst

Hooks Settings
``````````````
.. include:: conf/hooks.rst

File Extensions
```````````````
.. include:: conf/extensions.rst

Playbook Settings
```````````````
.. include:: conf/playbooks.rst

.. seealso::

    `User Mailing List <https://www.redhat.com/mailman/listinfo/linchpin>`_
        Subscribe and participate. A great place for Q&A
    `irc.freenode.net <http://irc.freenode.net>`_
        #linchpin IRC chat channel
