This OpenSeadragon ( http://openseadragon.github.io/ ) plugin provides 
a scale bar which adjusts depending on the zoom level.

A demo is available here: http://nistdeepzoom.github.io/OpenSeadragonScalebar/

It can be used like this:
`````javascript
var viewer = new OpenSeadragon.Viewer(...);
viewer.scalebar({
  minWidth: ...,
  pixelsPerMeter: ...,
  color: ...,
  ...
});
`````

To change any property, just call viewer.scalebar with the updated property.
For example, to change the pixelsPerMeter:

`````javascript
viewer.scalebar({
  pixelsPerMeter: ...
});
`````

The list of all the options can be found and tested on http://nistdeepzoom.github.io/OpenSeadragonScalebar/
If type, pixelsPerMeter or location are not set (or set to 0), the bar is hidden.


Disclaimer:

This software was developed at the National Institute of Standards and
Technology by employees of the Federal Government in the course of
their official duties. Pursuant to title 17 Section 105 of the United
States Code this software is not subject to copyright protection and is
in the public domain. This software is an experimental system. NIST assumes
no responsibility whatsoever for its use by other parties, and makes no
guarantees, expressed or implied, about its quality, reliability, or
any other characteristic. We would appreciate acknowledgement if the
software is used.

[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/d88cd6c96d35f934cde718826296abca "githalytics.com")](http://githalytics.com/NISTDeepZoom/OpenSeadragonScalebar)
