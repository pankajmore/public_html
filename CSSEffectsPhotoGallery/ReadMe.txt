### CSS Effects: Photo Gallery ###

===========================================================================
DESCRIPTION:

This sample shows how you can create immersive, compelling photo galleries using CSS effects, including transitions, animations, and transforms.

===========================================================================
BUILD REQUIREMENTS:

None.

===========================================================================
RUNTIME REQUIREMENTS:

Safari 4 or later, iPhone OS 3.1 or later

===========================================================================
PACKAGING LIST:

photo-gallery.html
  Main HTML file.

scripts:
    gridview.js
      JavaScript object for creating a grid of elements. Used for the thumbnail view in the gallery.
    photo-data.js
      JSON describing the images and metadata
    photo-gallery.js
      Main JS file which creates the SlideShow, and does event handling.
    slideshow.js
      Contains SlideShow object which contains most of the gallery logic.
    tile-transition.js
      Script for some more advanced tile transitions.
    transitions.js
      Script for basic transitions.
    utilities.js
      Some JavaScript utilities.

style:
    gallery-ipad.css
      Custom CSS styles for iPad
    photo-gallery.css
      Styling for the photo gallery.
    shared.css
      Styling for the main page.
    tile-transitions.css
      Styles related to more advanced tile transitions.
    transitions.css
      Styles related to the gallery transitions.

===========================================================================
CHANGES FROM PREVIOUS VERSIONS:

Version 1.1
- Minor cleanup.
Version 1.0
- First version.

===========================================================================
Copyright (C) 2010 Apple Inc. All rights reserved.
