# Instant Jasmine Coffee

*A [CoffeeScript](http://jashkenas.github.com/coffee-script/ "CoffeeScript") skeleton project for test-driving with [Jasmine BDD](http://pivotal.github.com/jasmine/ "Jasmine: BDD for Javascript | Jasmine")*

## Requirements
Based on the change to module management in [`npm` v1.0+](http://blog.nodejs.org/2011/03/23/npm-1-0-global-vs-local-installation/ "npm 1.0: Global vs Local installation &laquo; node blog"), the following modules are now local to this project:

* [coffee-script](https://github.com/jashkenas/coffee-script)
* [uglify-js](https://github.com/mishoo/UglifyJS)
* [growl](https://github.com/visionmedia/node-growl), which requires [growlnotify](http://growl.info/extras.php#growlnotify "Growl - Extras") to be available on your `PATH`

You shouldn't have to install them with `npm`.  If it's annoying to require Growl, it's simple to remove.  I think it's a useful task for OS X users and other OS variants probably have similar node modules for hooking into other native notification systems.

## Usage

From project root:

    cake watch:all

That's it.  Hack away and run your test suite with `SpecRunner.html`.  There are several other tasks in `Cakefile` that you can checkout in the source, or simply execute:

    cake

for a few short descriptions.

## More Info

I've written a couple of posts about this skeleton project where you can learn more about why and how you can make use of it.

* [new post]
* [Flavored Coffee: Test Driving Client-side Development with Jasmine &amp; CoffeeScript](http://goo.gl/aeCV5 "Flavored Coffee: Test Driving Client-side Development with Jasmine &amp; CoffeeScript | Visibiz")
