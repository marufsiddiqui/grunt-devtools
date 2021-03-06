grunt-devtools (preview)
==============

grunt-devtools

## Quick Setup

* Download the [Grunt Devtools](https://chrome.google.com/webstore/detail/grunt-devtools/fbiodiodggnlakggeeckkjccjhhjndnb?hl=en)
add-on for Chrome Dev Tools from the Chrome Web Store.

* `npm install grunt-devtools` in your grunt project

* Add `grunt.loadNpmTasks('grunt-devtools');` to your `Gruntfile`

* run `grunt devtools`

* open Chrome Dev tools, find the Grunt tab. Your grunt tasks should now be accessible from Chrome.



## Dev Setup

### Chrome Extension

Load unpacked extension from the `extension` folder.

### Grunt Plugin Installation

Locally install the plugin using `npm install [folder]/grunt-plugin`

Add `grunt.loadNpmTasks('grunt-devtools');` to your `Gruntfile`

Run `grunt devtools` to get things rolling!

### Preview Screenshots

![](http://v14d.com/i/512f287f30388.jpg)

![](http://v14d.com/i/512f28f92eef4.jpg)

![](http://v14d.com/i/512f29c259903.jpg)

![](http://v14d.com/i/512f2a4d7e8f0.jpg)

### Current Limitations & Issues

* The extension will work for up to 5 instances of `grunt devtools` at a time
(this means if you like to work on more than 5 projects at a time, you will need to turn off the task)

* Unable to view output for background tasks ( work in progress...) and other output issues

### Release History

* 0.1.0.4 - Adding Background Task support. You can now press `(B)` to send
the task into background and continue running other tasks.
* 0.1.0-alpha3 - Adds `Gruntfile.coffee` support

