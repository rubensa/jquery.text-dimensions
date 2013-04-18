TextDimensions - A jQuery text dimensions measure plugin
======================

*TextDimensions* (```jquery.text-dimensions```) is a simple jQuery Plugin to measure text dimensions
in an HTML context.

It's simple to use.

Just add the following line to get width and height of ```Get my dimensions``` text if you add 
it inside the named div ```myDiv```:

```javascript
var dimensions = $('div#myDiv').textDimensions('Get my dimensions');
```

*TextDimensions* is as simple as it gets:

 * 100% JS with zero dependencies and no external CSS.
 * Easy to understand

If there is a ```context``` ('div#myDiv' in example), ```context``` font is used to measure text dimensions.
If there is no ```context``` element ($.textDimensions('Sample text')) default font is used to measure text dimensions.

###Usage
```javascript
var dimensions = $('div#myDiv').textDimensions('Get my dimensions');
alert("width: " + dimensions.width + ", height: " + dimensions.height);
```

###Install
This plugin is very light weight. You can just download the 
[jquery.text-dimensions.js](https://raw.github.com/rubensa/jquery.text-dimensions/master/jquery.text-dimensions.js)
and add it to your page.

###Release History

**2012-04-18** - Initial public release.


###License
The same as JQuery...

jQuery Plugin: TextDimensions
https://github.com/rubensa/jquery.text-dimensions/
 
Copyright (c) 2013, Ruben Suarez Alvarez http://blog.rubensa.eu.org/
Dual licensed under the MIT or GPL Version 2 licenses.
http://jquery.org/license
