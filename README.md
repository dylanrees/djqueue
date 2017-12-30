Just a little something I'm playing around with.
The idea is the following: create a program that suggests new music to listed to out of your own music library based on what you have been listening to.

[how music recomendation works - and doesn't work](https://notes.variogr.am/2012/12/11/how-music-recommendation-works-and-doesnt-work/)

## step 1: music suggestion backend
come up with some sort of framework for taking data about what music is playing, collecting it, and suggesting what to play next. probably it's based on bayesian inference on the data, [done in python](http://www.bayespy.org/).

## step 2: interact with a music player
you can start simple - [mpd](https://www.musicpd.org/) and the program would pass commands to it via [mpc](https://musicpd.org/clients/mpc/).  maybe a primitive frontend using something like [curses](https://docs.python.org/2/howto/curses.html) or [wxpython](https://wxpython.org/screenshots.php).

## step 3: write plugin
turn it into a plugin for a music player. probably [rhythmbox](https://wiki.gnome.org/Apps/Rhythmbox/Plugins/WritingGuide), since it supports writing plugins in python.

## step 4: keep making it smarter
use [more sophisticated algorithms](https://towardsdatascience.com/best-python-libraries-for-machine-learning-and-data-science-part-1-f18242424c38) for suggesting things. 
