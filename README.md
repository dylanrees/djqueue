Just a little something I'm playing around with.
The idea is the following: create a program that suggests new music to listed to out of your own music library based on what you have been listening to.

## music player backend
mpd (music player daemon) and the program would pass commands to it via mpc.

## music suggestion backend
for each song, it suggests the best song to play next.  probably at first it just relies on counts of which songs you tend to listen to after which others.  after that maybe it gets move complex, incorporating machine learning.

## frontend

CLI at first.

https://docs.python.org/2/howto/curses.html

https://wxpython.org/screenshots.php
