First Visit Js
==========

Tiny jQuery plugin to show hints and tips for users on their first visit to a page.

How to use
-------------

* Add a reference to jquery
* Add a reference to first-visit.js to head section of your page:

        <script src="first-visit.js"></script>

* Init first-visit.js:

        $(function() {
            $('.hint').firstVisit();
        });

Options
-------

* `classToAdd` - you can add your own class when showing an element. Example:

        $(function() {
			$('.hint-for-newbies').firstVisit({
			    classToAdd: 'yellow-background'
			});
        });


License
---------

MIT


