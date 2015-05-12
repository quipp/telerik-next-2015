# HTML5 Mobile Web Performance

* Presenter - Dave Arel (Chef Made - chef prepared food in freezer)
* Problems with native
	* Deployment expensive (iPads)
	* Innovation slowed
	* Bugs kill activity
* Hybrid - feed in web pages inside native app.
* They created Bootloader - to distribute new HTML/CSS.
* HTML5 - how browsers work -> html5rocks.com  
* Painting -> create in memory (CPU intensive)
* Drawing -> put on screen (fast)
* CPU paints bitmap -> CPU upload to GPU
	* GPU = awesome
* Layers / backing store
* Don't want everything on a GPU layer because too much memory.
* CSS hardware accelerating can be done via CSS, but requires hacky solutions.
	* Redraw -> no repaint.
* Caching - create once, move off screen, the move on when needed.  Avoid redoing.
* Switch from rdgb to transparency -> there's lots of hacks like this...

