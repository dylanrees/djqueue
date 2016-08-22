Just a little something I'm playing around with.
The idea is the following: create a program that suggests new music to listed to out of your own music library based on what you have been listening to.
It might employ machine learning.

First I'll get it to work with Goggles Music Manager.
Here's what you'll do:

* Copy all your "recently played" into a playlist.
* Save that playlist as a .csv file.
* Load that file into learning.py
* Generate a playlist with playlist.py

Sometime you'll listen to the same artist for a while, so I'll eliminate the posibility of playing the same artist twice in a row.

There should probably be a feature that avoids re-using the same song played at the same time in the future.  just in case you use a partially-updated version of the same playlist

===resources for later===

https://docs.python.org/2/howto/curses.html

https://wxpython.org/screenshots.php