ios-grid-system
===============

Fireworks grid system for designing iOS apps.

About the iOS Grid System
===============

It’s optimized to create designs for all Apple mobile devices (in both portrait and landscape modes) as of December 2012. It will be also updated as new iOS devices and resolutions arrive.

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

The command will not interfere with your existing artwork, but it will resize your canvas, so this is something to keep in mind. 

You can use any of these commands multiple times in one document. Just create a new page and select the command you wish to run. That’s it!

How to install and use it
===============

1. Get the files from GitHub or right here at Smashing Magazine.
	-  If you’re downloading from Smashing Magazine, unzip the file.
	- If you’re pulling the files from GitHub, you can download a zipped file or clone the repository directly onto your machine. Here’s the command you’ll use in the command line: <pre>git clone git@github.com:joshuamauldin/ios-grid-system.git</pre>
2. Move your files into the following directory: 
	- For Mac users: Applications » Fireworks CS6* » Configuration » Commands
	- For Windows users: Local Disk » Program Files (x86) » Adobe » Adobe Fireworks » Configuration » Commands
3. Open Fireworks and create a new document
	- As previously mentioned, the size doesn’t matter. The command will resize your page accordingly.

I'm curious to see how and where you use it. Send me a link to your app a mobile site. I'd love to see it. Enjoy!