# Sitefinity Performance - Planning of Peak Online Traffic for NFL's Biggest Games

* Presenter - Rob Sanders
* American Eagle - software consulting.
* Got 85k on 6 servers - Windows probably.
	* Used CDN for static content...
	* Deliberately create fixed HTML pages if know it doesn't change - skip database.
* They had 1000 people test the site...  Didn't use automated tool
* Had to customize cache profile.
* Used Load Storm
* Tested against live data.
* Must use all the tricks of minimizing DB, caching, etc for performance.

Questions
* I wonder how much better this would have worked with elastic cloud...  and how much it would have cost.

