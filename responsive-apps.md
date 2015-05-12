# Responsive Apps

* Kendo UI is client-side (HTML/JS)
* jQuery based.
* Responsive
* Responsive web design
	* About 50% of traffic is mobile - not an option to skip it.
	* Should worry about TV / game consoles / Kindle.
	* Techniques
		* Grid-based layouts
			* 12 column design system
			* RadPageLayout
		* Media queries (most important)
			* meta name viewport => Don't use scale/zoom.  Do use width=device-width
			* Choose which CSS is used and when.
			* Easiest with width of ViewPort.
		* Flexible images
			* Largest cost for downloads.
			* max-width 100%
			* Dynamically select appropriate size.
		* Show/hide content
	* UI Components (certain controls support some behaviors)
		* Fluid - control with 100% of parent width.
		* Responsive - auto resize.
		* Elastic - font size change (em).
		* Adaptive - change layout automatically.
		* Controls
			* RadGrid - fluid and adaptive.
				* RenderMode
			* Grid and scheduler are best with adaptive.
	* RadDeviceDetectionFramework - tool for code behind.
	* RadPageLayout
		* Server side.
		* adjusts based on physical size.
	* RWA VS Template - good example.
	* Full example - Telerik Demo for Trip Advisor.
	* Kendo UI
		* Responsive
		* Bootstrap integrated
		* .resize() to rerender.
		* Mobile components are for mobile-only situations (optimized).  Default controls are responsive.
			* Style changes automatically for device - cool.
		* Responsive Panel Widget
			* Automatic toggle menu.

Questions
* How does this compare to competitors - jQuery Mobile / Twitter Bootstrap?
* How does licensing work?  Core is open source - I'm not sure what isn't open source.

