Filename = userChrome.css

In Linux, FireFox tends to default to a very small font size in the URL bar, and doesn't leave much padding around the menubar and bookmark bar.

This is a .css file to:
	(1) increase the font size in the URL bar
	(2) increase the padding on the menu bar
	(3) increase the padding on the bookmarks bar

This css solves the problems without using a plugin.

The font referenced is Overpass, but any font family will do.  10pt font is nice on 1920x1080 monitor.  Adjust less or more to taste.

This file must be placed in /home/user/.mozilla/firefox/[name.default]/chrome/

The [name.default] directory is usually something ugly like fldhf7u8.default.  Enter it and create the chrome directory, then place the .css file inside.
This directory is based on a Linux install.  Windows users are welcome to contribute here too.
