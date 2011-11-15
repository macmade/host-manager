host-manager - version 1.0
==========================

Copyright (c) 2011 eosgarden - Jean-David Gadina <macmade@eosgarden.com>

**A command-line utility to manage the /etc/hosts file.**

    Usage: ./build/bin/host-manager COMMAND [ARGUMENTS]

Available commands:
-------------------

    -h / --help        Print the help dialog.
    -v / --version     Print the version number.
    -a / --add         Add an entry to the /etc/hosts file.
    -r / --remove      Remove an entry from the /etc/hosts file.

Adding an entry to the /etc/hosts file:
---------------------------------------

    host-manager -add host address

Removing an entry from the /etc/hosts file:
-------------------------------------------

    host-manager -remove host

Examples:
---------

    host-manager -add www.example.org 127.0.0.1
    host-manager -remove www.example.org
