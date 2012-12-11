gsettings-load
==============

A simple ruby script to load predefined configurations into gsettings.

This script can be used to load a set of configurations into the current user's Gnome dconf settings. It simply wraps the gsettings command line tool.
An example of each type of gsetting is included in the file. The actual setting could be in its own file and distributed to users via puppet or chef.