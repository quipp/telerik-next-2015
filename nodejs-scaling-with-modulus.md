# Node.js Scaling with Modulus

* Based on this slide show http://slides.com/taronfoxworth/deck-4#/
* How does Modulus compare to Heroku, Amazon, Azure?
	* Can scale out immediately to other locations.
	* Better debugging.
	* Uses Docker behind the scenes.
	* Just getting started with Java and PHP tomorrow.
	* Does this all run on other clouds?  Yes.
	* Does it run on Azure?  Yes.
	* Modulus is a Platform as a service.
	* Price is the same.
	* Heroku (main competitor) 
		* only supports AWS.
		* Cannot run locally.
		* Infrastructure not based on Docker.
	* Presenter - taron@modulus.io
* Node.js is just server-side JavaScript - runtime.
	* Libuv is what adds the server side capabilities to Node.js.
		* Node is single threaded, but Libuv is not.
		* Can use cluster module to get node to use multiple CPU.
* Created sample Airlines application via Telerik Platform.
	* Built on Cordova / Phone Gap.
* Using Yeoman - scaffolding tool.  Makes it easy to throw together rest service.
	* Uses Bower and Grunt.
	* Can install stuff from GitHub
	* We are using rest-express from https://github.com/brianviveiros/generator-rest-express
* Couldn't finish demo because couldn't log into modulus via node plug-in...


ThoughtWorks didn't recommend this type of cloud solution because it doesn't tap into cloud specific features - only stateless website.  It's really just Docker/Virtual Machines for stateless websites.
