ios-grid-system
===============

Fireworks grid system for designing iOS apps.

About the iOS Grid System
===============

The extension is made for Adobe Fireworks and is optimized to help you create designs for all Apple mobile devices (in both portrait and landscape modes) as of February 2013. It will be also updated as new iOS devices and resolutions arrive.

For clarity, here's what's included in the package:

  - Non-Retina iPhone (3GS), 320 x 480 px
  - Retina iPhone (4, 4s), 640 x 960 px
  - Retina iPhone (5), 640 x 1136 px
  - Non-Retina iPad (1, 2, Mini [2012]), 1024 x 768 px
  - Retina iPad (3, 4), 2048 x 1536 px

>**Note:** When working on an iOS app design, Apple doesn't allow us to specifically target the screen of the iPad Mini. If you want to work on a design for an iPad Mini, you can simply use the Non-Retina iPad resolution (which is 1024 x 768 px, for iPad 2 and iPad 1).



How The Extension Works
===============

When run, the iOS Grids extension will automatically create two things: **guides** and **shapes**. The shapes are placed on their own layer in the page. Shapes are added as a symbol in Fireworks, so it's easy to reuse them anywhere else in your Fw PNG document, if that's your thing.

<h4>1. Guides</h4>

A set of <em>guides</em> will be placed directly on the page.

You can lock them (menu <code>View &rarr; Guides &rarr; Lock Guides</code>), you can activate snap-to-guides (menu <code>View &rarr; Guides &rarr; Snap to Guides</code>), which can make easier moving and resizing of objects on the page, and you can temporarily hide or show the guides (menu <code>View &rarr; Guides &rarr; Show Guides</code>).


<h4>2. "Grid" Layer</h4>

The <em>shapes</em> (which will serve as columns) will be placed on their own, locked layer in the page, named "Grid", and combined into one symbol. Because the shapes are added as a symbol, it's easy to re-use them anywhere else in your document, if that's your thing.

The columns in the "Grid" layer have 33% transparency and objects in your design, placed on layers underneath it, will be visible, but you can move this layer to the bottom of the layer stack, if you prefer.

And when you don't need the "Grid" layer being visible, you can simply toggle its visibility in the Layers panel.

How to install and use it
===============

1. Get the files from GitHub or right here.
2. Move your files in the *iOS Grid System* folder into the following directory: 
	- For Mac users: Applications » Fireworks CS[x] » Configuration » Commands
	- For Windows users: Local Disk » Program Files (x86) » Adobe » Adobe Fireworks » Configuration » Commands
3. Open Fireworks and create a new document
	- As previously mentioned, the size doesn’t matter. The command will resize your page accordingly.

I'm curious to see how and where you use it. Send me a link to your app a mobile site. I'd love to see it. Enjoy!