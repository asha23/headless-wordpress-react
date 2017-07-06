
# Wordpress Seed Theme

This is a simple Bootstrap seed theme with Bower and Gulp dependency and build management. I have removed all bloat and unnecessary code from this theme, so it doesn't have multilanguage support, widgets, sidebars or any other WordPress bloat. It should be considered a base theme for developing using Advanced Custom Fields and using WordPress as a pure CMS.

Why did I remove the Widgets and such? Well, I very rarely use widgets. You could easily add the functionality back in. But this is a stripped to the absolute bone theme, with the common items I personally use on a daily basis. Sidebars and Widgets don't figure all that much in my workflow, so they are history.

You might find my choices of JS libraries arbitrary as well. However, the ones I have included in the Bower file are ones I use for pretty much every project. They are in the main bulletproof and I've thoroughly tested them. Again, you are welcome to use your own preferred sets of stuff, simply edit the bower.json file.

I personally like Bootstrap. It does what I need it to do. I've used the grid on so many projects now that I consider it pretty much bulletproof. So the skeleton of this theme is Bootstrap sass. It's probably a big job to retrofit another framework into this theme, so you are probably best off rolling your own for Suzy/Foundation etc.

This utilises Yarn for dependency management - https://yarnpkg.com/

Once you have installed it, simply run:

	yarn   
	bower install   
	gulp

	gulp watch

And you should be good to go.

#### Javascript libraries I've included

* jQuery
* Bootstrap Sass
* Lightgallery
* Fontawesome
* Imagesloaded
* Slick Carousel
* Respond.js
* Enquire.js
* MatchHeight
* Cycle 2
* Isotope

Feel free to add your own via Bower.

#### Advanced Custom Fields

This theme probably requires Advanced Custom Fields Professional. Which if you don't have already, you should get.

Remove the contents of ```acf-json``` if you want to start from scratch. But this simply sets up some initial theme options.

#### General

The views folder is intended as a place to add content types for the theme.
