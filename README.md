HostManager
===========

[![Build Status](https://img.shields.io/travis/macmade/host-manager.svg?branch=master&style=flat)](https://travis-ci.org/macmade/host-manager)
[![Issues](http://img.shields.io/github/issues/macmade/host-manager.svg?style=flat)](https://github.com/macmade/host-manager/issues)
![Status](https://img.shields.io/badge/status-inactive-lightgray.svg?style=flat)
![License](https://img.shields.io/badge/license-boost-brightgreen.svg?style=flat)
[![Contact](https://img.shields.io/badge/contact-@macmade-blue.svg?style=flat)](https://twitter.com/macmade)  
[![Donate-Patreon](https://img.shields.io/badge/donate-patreon-yellow.svg?style=flat)](https://patreon.com/macmade)
[![Donate-Gratipay](https://img.shields.io/badge/donate-gratipay-yellow.svg?style=flat)](https://www.gratipay.com/macmade)
[![Donate-Paypal](https://img.shields.io/badge/donate-paypal-yellow.svg?style=flat)](https://paypal.me/xslabs)

About
-----

A command-line utility to manage the /etc/hosts file.

Documentation
-------------

### Usage:

    host-manager COMMAND [ARGUMENTS]

### Available commands:

    -h / --help        Print the help dialog.
    -v / --version     Print the version number.
    -a / --add         Add an entry to the /etc/hosts file.
    -r / --remove      Remove an entry from the /etc/hosts file.

### Adding an entry to the /etc/hosts file:

    host-manager -add host address

### Removing an entry from the /etc/hosts file:

    host-manager -remove host

### Examples:

    host-manager -add www.example.org 127.0.0.1
    host-manager -remove www.example.org


License
-------

HostManager is released under the terms of the Boost Software License - Version 1.0.

Repository Infos
----------------

    Owner:			Jean-David Gadina - XS-Labs
    Web:			www.xs-labs.com
    Blog:			www.noxeos.com
    Twitter:		@macmade
    GitHub:			github.com/macmade
    LinkedIn:		ch.linkedin.com/in/macmade/
    StackOverflow:	stackoverflow.com/users/182676/macmade
