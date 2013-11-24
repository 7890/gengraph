==============
 INTRODUCTION
==============

The "gengraph" is a bash script which generates static function call
graph for C source code.

The "install.sh" is a bash script which installs all necessory 
components required to run "gengraph". It additionally copies the
the "gengraph" to /usr/local/bin.

=================================
 INSTALLATION AND UNINSTALLATION
=================================

To install, simply run following command.

sudo ./install.sh

To uninstall, run following command.

sudo ./install.sh -u

(NOTE: uninstalling will also remove graphviz component from your system
       , if you want to uninstall "gengraph" then, simply remove sript
       from /usr/local/bin directory.)
       
=======
 USAGE
=======

Run gengraph -h for help.
