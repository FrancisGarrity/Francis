---
layout: post
title: Exploring Geological Modelling - Leapfrog Geo Part 2
description: >

---
Tutorial 2: Introduction to Leapfrog Geo: Modelling Veins
<iframe frameborder="0" allowfullscreen="allowfullscreen" width="768" height="432" src="https://www.youtube.com/embed/B36YXn4n6zc?autoplay=1&loop=1&menu=0&controls=0&showinfo=0&autohide=1&playlist=B36YXn4n6zc"></iframe>

The aim of this tutorial is to import drillhole data and use it to build two geological models of a series of veins and
the lithologies in which they occur. In the first model we're shown how to build individual veins, while the second model demonstrates the generation of veins as part of a vein system.

In order to set up the project, we are taught to georeference an aerial photo, set a clipping boundary and drape the aerial photo over a digital elevation model. We then import drillhole data (including the Hole ID, X, Y and Z coordinates, maximum depth, initial depth, dip, azimuth and lithology). Gaining familiarity with the formatting and variables in these files has been useful from an exploration perspective - I will now be able to report field data in a way that can be directly imported to geological software, thus saving the project geologist's time.

The next task is to analyse the drillhole data. An important note is that contact surfaces should be defined by starting with the oldest unit and working up. A typical workflow for defining the model involves Generating contact surfaces that correspond to the boundaries between lithological units, refining the contact surfaces, arranging them in chronological order, and then finally using  the surfaces and the chronological order to divide the geological model into units. Contact surfaces can be set to interact with other surfaces in various ways - these include "deposit contact surfaces", "erosion contact surfaces", "intrusion contact surfaces" and "vein contact surfaces".

-F. D. A. Garrity, MSc

<html>
  <head>
  </head>
   </body>
   <script>
<!-- DC Flickr Feed Start -->
<div id="dc_jflickr_feed_container" style="width:80%;">
  <ul id="jflickr_cbox" class="dc_jflickr_thumbs"></ul>
</div>
<!-- DC Flickr Feed End -->
<div class="dc_clear"></div> <!-- line break/clear line --> 

<!-- DC Flickr Feed Settings --> 
<script type="text/javascript">
	$('#jflickr_cbox').jflickrfeed({
		limit: 16, // number of images to show
		qstrings: { id: '160787014@N06' // id of flickr gallery (use idgettr.com to get flickr gallery id)
		},
		// Small images: {{image_s}}
		// Medium images: {{image}}
		// Large images: {{image_b}}
		itemTemplate: '<li>' + '<a rel="colorbox" href="{{image_b}}" title="{{title}}">' + '<img src="{{image_s}}" alt="{{title}}" />' + '</a>' + '</li>'
	}, function(data) {
		$('#jflickr_cbox a').colorbox();
	});
</script>
</html>


<html>
  <head>
    <meta name="viewport" content="user-scalable=no, width=device-width, initial-scale=1, maximum-scale=1">

    <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

    <link href="https://unpkg.com/nanogallery2/dist/css/nanogallery2.min.css" rel="stylesheet" type="text/css">
    <script type="text/javascript" src="https://unpkg.com/nanogallery2/dist/jquery.nanogallery2.min.js"></script>

  </head>
  <body>
  
    <div ID="ngy2p" data-nanogallery2='{
        "userID": "160787014@N06",
        "kind": "flickr",
        "photoset": "72157704488657865",
        "thumbnailOpenOriginal": true,
        "thumbnailWidth": "200",
        "thumbnailBorderVertical": 0,
        "thumbnailBorderHorizontal": 0,
        "thumbnailLabel": {
          "display": false
        },
        "thumbnailAlignment": "center"
      }'>

    </div>
    
  </body>
</html>

