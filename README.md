mediacenterjs
=============

A HTML/CSS/Javascipt (NodeJs) based Mediacenter

![Donate] (screenshots/paypal-donate.gif) https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=DHV3M4SST8C5L

Screenshots: 

![Dashboard] (screenshots/interface.jpg)

![Movies] (screenshots/movies.jpg)

Status: 
=======

Heavy work in progress
		
What works?
===========

* Basic Routing
* Basic MVC Framework
* Present inital setup
* Show time and date
* Basic App framework
* Automated dashboard
* Basic keyboard controls
* Onscreen keyboard
* Movie indexing
* Display movies with art
* Local caching
* Display movie information
* Weather information (Only in Dutch)

What's comming up
=================

* Settings
* transcoding
* Screensaver 

What's not working
==================

* The rest...


What is the goal/purpose:
MediacenterJS is/will be a mediacenter like for instance XBMC but based 100% on frontend techniques(HTML5/CSS/Javascript) and languages.
The backend is based on Nodejs/ExpressJS 3x with jade templates producing easy to use and code for end product. 
The goal is to make it possible to add a 'app' to MCJS even with limited knowlegde of said frontend techniques.
Asside from that, due to the use of node, MCJS is/will be very fast and highly customizable.

The actual playing of the video will be possible with different utilities. 
If using a smart TV, a upnp connection will be established. If using an standard tv with, for instance Rasberry PI, VLC wil be used to play the video. 

This application will run on Windows and Linux based systems. 
There will be a specific Linux distro for raspberry pi using a kiosk, debian distro.

Basic featurelist:

* Multiple apps like youtube, weather stopify etc.
* Movie database with information and playback
* Music database with information and playback
* TV show database with information and playback 
* Easy to use app framework
 
For questions/contributions feel free to email me at: jansmolders86@gmail.com
this application uses the GNU General Public License. See <http://www.gnu.org/licenses/>.

Copyright (C) 2013 - Jan Smolders
