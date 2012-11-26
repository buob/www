Editing the homepage for Marionette.js
=============


Installation
-----------

This website is built using Middleman (http://middlemanapp.com), Sass and Compass.  All the dependencies are automatically installed with the help of Bundler.

    git clone …
		cd ordner
		bundle


How to update the site?
-----

		middleman server

and point your browser to http://localhost:4567


How to Build and Deploy a new version of the site?
-----

		middleman build --clean
		middleman deploy


How to populate a new version of the Marionette.js builds?
-----

There is a little bash script that collects and compresses all the files and adds the new version number on the site.

		./build-marionette 1.0.0-beta6