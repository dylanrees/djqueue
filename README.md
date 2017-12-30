Just a little something I'm playing around with.
The idea is the following: create a program that suggests new music to listed to out of your own music library based on what you have been listening to.

[how music recomendation works - and doesn't work](https://notes.variogr.am/2012/12/11/how-music-recommendation-works-and-doesnt-work/)

## music player backend
mpd (music player daemon) and the program would pass commands to it via mpc.

## music suggestion backend
for each song, it suggests the best song to play next.  probably at first it just relies on counts of which songs you tend to listen to after which others.  after that maybe it gets move complex, incorporating machine learning.
probably it's based on bayesian inference on the data, [done in python](http://www.bayespy.org/). 

## frontend

CLI at first.

https://docs.python.org/2/howto/curses.html

https://wxpython.org/screenshots.php
