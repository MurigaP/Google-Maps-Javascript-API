Google Maps Javascript API
=======

###Gmaps.js library  simplifies your life in spatial coding, Write less, Do More!!!!.
-----
####Geo-developing has got no better than this, and never will, given Google map is to be plugged into your website.

#Features:
* Basic Javascript/jQuery syntax
* Extensive Documentation
* Scalable
* Platform Independent(Works well in any browser)
* Dependable Community
--------
##Dependancies / Requirements:
1. jQuery plugin
2. gmaps.js
3. Bootstrap
4. Google Maps API




Go to official API Documentation [hpneo.github.io/gmaps/documentation.html](http://hpneo.github.io/gmaps/documentation.html)

Quick Start
-----

1. Add a reference to Google Maps API
2. Add gmaps.js in your HTML
3. Register API Key with Google and include it in your site
4. Enjoy!

```html
<!DOCTYPE html>
<html>
<head>
  <title>Gmaps API - Life made simple</title>
  <link rel="stylesheet" href="http://twitter.github.com/bootstrap/3X/bootstrap.min.css" />
  <style type="text/css">
    #map {
      width: 400px;
      height: 400px;
    }
  </style>
</head>
<body>
  <div id="map"></div>
<!-- Other Website Contents -->
</body>
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/2.4X/jquery.min.js"></script>
<script src="http://twitter.github.com/bootstrap/3X/bootstrap.min.js" ></script>
<script src="http://maps.google.com/maps/api/js?key=YOUR_API_KEY"></script>
<script src="gmaps.js"></script>
<script>
  var map = new GMaps({
    el: '#map',
   lat: -0.427787,
   lng: 36.9432071
  });
</script>
</html>
```


License
---------
MIT License. Copyright 2014 Gustavo Leon. http://github.com/hpneo

Permission is hereby granted, free of charge, to any
person obtaining a copy of this software and associated
documentation files (the "Software"), to deal in the
Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the
Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice
shall be included in all copies or substantial portions of
the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY
KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
