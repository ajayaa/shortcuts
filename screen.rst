Copy buffer to a file
=====================
Ctrl + a and : to get to command mode, then

hardcopy -h <filename>

New named screen
================
screen -S <name>

new split + new command
=======================
Ctrl + a and (S|V) and Ctrl + a c


Change name of existing screen
==============================
Ctrl + a and : sessionname <newname>

Change a window name in a screen
================================
Ctrl + a and A

Create a new window
===================
Ctrl+a and c

create a new tab
================
screen -t <tab_name>

pass a command to a screen session
==================================
screen -S <session_name> -X <command>

e.g. delete a screen session altogether
screen -S 23536 -X quit
