fglrx_fan
=========

A python daemon to control excessive fan speeds when using fglrx.

The script runs as a background python process, using the python-daemon library. It provides 5 parameters for GPU temperature ranges, and 5 parameters for fan speeds. The user can add to or modify these ranges, which are stored in two lists at the top of the script. For simplicity's sake, a user only has to add a line to their .bashrc file (ie: 'python ~/folder/fanspeed.py'), and the program will run in the background. It is reccomended that a user customize the temperature and speed values to appropriate ranges for their GPU. The test card was an XFX HD 6800.

Usage: Insert the path of fanspeed.py into .bashrc for the desired user(s), and ensure that the file has been chmoded to have the necessary privileges for execution. e.g.: put 'python ~/folder/fanspeed.py' on a new line in .bashrc.

Feedback or feature requests are welcome.


