=========
OpenSMTPD
=========

Install OpenSMTPD via the OS' package management,
generate configuration file, start service.

Tested with OpenSMTPD 5.7.3 in relay-only config on:
  - FreeBSD 10.2
  - CentOS 6.7

.. note::

    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html>`_.

Available states
================

.. contents::
    :local:

``opensmtpd``
-------------

Runs the states to install OpenSMTPD, creates the configuration
file and starts the service.

.. note::

    db-type table files aren't created yet and the configuration
    file is missing templating for almost any setting needed
    for basic operations.
