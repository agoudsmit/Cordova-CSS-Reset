Cordova-CSS-Reset
=================

CSS Resetter adapted to Cordova & Phonegap projects including :

* Making link selections transparent
* Preventing callout to copy image
* Preventing webkit from resizing text to fit
* Preventing copy paste (add a `body { -webkit-user-select: text; }` to allow it)
* Activating GPU rendering (way faster than CPU)

Installation
------------

### Bower

`bower install cordova-css-reset`

Releases Notes
--------------

* Version 2.1 (08/10/2013) : + `textarea { resize: none; }` to avoid textarea resizing. 
* Version 2.2 (02/12/2013) : + `a { outline: none; }` to avoid dots around links. 
* Version 2.3 (03/12/2013) : I implemented many stuff from [YUI 3.5.0 reset.css](http://yuilibrary.com/yui/docs/cssreset/). 
* Version 2.4 (21/01/2014) : + `body { -webkit-font-smoothing: antialiased; }` to avoid aliasing on Chrome. 
* Version 2.5 (28/01/2014) : + `a { color: inherit; text-decoration: none; }` to avoid links auto-formatting. 
* Version 2.6 (23/11/2014) : + `button { margin: 0; padding: 0; border: 0; font-size: 100%; font: inherit; vertical-align: baseline; }` to avoid buttons auto-formatting. 
* Version 2.7 (20/12/2014) : + `body { font-size: 0; }` to avoid unwanted spaces between inline block elements. 
* Version 2.8 (21/04/2015) :
  * + `:focus { outline: none; }` to avoid glowing effect around form focused fields. 
  * + `body { -webkit-transform: translateZ(0); }` to activate mobile GPU for CSS rendering on Android & iOS.
