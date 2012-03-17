jQuery SELECT Replacement
================================

I got tired of not being able to style SELECTs easily. This is a bad attempt to fix that with some Javascript :-p

It's based on code from the site [Janko at Warp Speed](http://www.jankoatwarpspeed.com/post/2009/07/28/reinventing-drop-down-with-css-jquery.aspx). I've added a few changes of my own, and the results can be seen on the [sample page](http://blog.gatherage.com/sites/default/files/dropdown/index.html).

To use, include the CSS file from the desired style, a copy of jQuery, and a copy of dropdown.min.js. Add a class to the SELECTs you want to replace, and call the library in your JS as follows.

    $(".yourClass").dropdown();

TODO:
-----
* Better documentation
* Add destroy method and namespace event binding
* Handle "selected" attribute
* Add a custom scrollbar when the dropdown gets too long
* Mirror changes that happen to the original SELECT
* SELECT MULTIPLE
* Add [ARIA](http://en.wikipedia.org/wiki/WAI-ARIA) elements
* Keep selected value after page refresh
* Tie into jQuery UI
