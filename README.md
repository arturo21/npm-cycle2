# npm-cycle2
Getting Started

Download either the production version or the development version of Cycle2.

In your web page:

<!-- include NPM Cycle2 (jQuery + Cycle2) -->
<script src="http://path/to/your/copy/of/cycle2.js"></script>

...

<!-- declare a slideshow -->
<div class="cycle-slideshow">
    <img src="http://malsup.github.com/images/p1.jpg">
    <img src="http://malsup.github.com/images/p2.jpg">
    <img src="http://malsup.github.com/images/p3.jpg">
</div>

That's it! You don't need to write any script to initialize the slideshow, Cycle2 will auto-initialize if you use the class cycle-slideshow.
Documentation, Demos, Downloads and FAQ

Everything you need to know can be found here: http://jquery.malsup.com/cycle2/
Bower

To install Cycle2 via Bower:

bower install jquery-cycle2

The only file you will need (unless you're customizing) is build/jquery.cycle2.min.js

(Other files are available for advanced customization and you can read more about them on the download and advanced download pages.)
Build

If you want to make changes to Cycle2 and build it yourself, you can do so by installing the node build dependencies:

npm install