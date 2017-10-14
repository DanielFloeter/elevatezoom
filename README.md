[jQuery Zoom Plugin](http://www.elevateweb.co.uk/image-zoom/)
================================

elevateZoom - A jQuery image zoom plugin


## Getting Started

Include jQuery and the plugin on a page. Include your images and initialise the plugin.

### Modification: 
To use elevateZoom with img elements, they will need to be wrapped with another element, so that element has to be able to accept html, like <a>, <span>, <li>, <div>, etc. This excludes <img> elements (see below).
* The img dimentions are used from the element it is assigned to.
* ElevateZoom search for the img url inside the element it is assigned to.


```html
<span style="width:250px;height:150px;">
	<img src='images/small/image1.png' data-zoom-image="images/large/image1.jpg"/>
</span>

<script>
    $('span').elevateZoom();
</script>
```

For more information on how to setup and customise, [check the examples](http://www.elevateweb.co.uk/image-zoom/examples).

## License
Copyright (c) 2012 Andrew Eades
Dual licensed under the GPL and MIT licenses.
