jQuery Plugin: Multi Row Input
==============================
By Tom Holder - [http://www.simpleweb.co.uk](http://www.simpleweb.co.uk)

Overview
--------
This is a jQuery plugin to provide multi row data input for things such as supporting multiple phone numbers etc.

Usage
-----
First include the `jquery.multirow.js` file in your page.

    <script src="/path/to/jquery.js" type="text/javascript"></script>
    <script src="/path/to/jquery.multirow.js" type="text/javascript"></script>

Then apply the multirow plugin to the page.

    $('.multiRowInput').multiRowInput();

The plugin operates on entire rows of elements, so the `.multiRowInput` element in the expression above could be a div containing an input and a label.

Extend
------

Works with TipTip and Labelify plugins to improve the experience further:

[tipTip](http://code.drewwilson.com/entry/tiptip-jquery-plugin)

[Labelify](http://github.com/glennfu/jquery.labelify)

Background
----------

This plugin was built for our fabulous ContactZilla product! ([http://contactzilla.com/]())

![Example](http://github.com/simpleweb/jQuery-Multi-Row-Input/raw/master/example.png)

License
-------
This plugin is licensed under both the GPL and MIT licenses. Choose which ever one suits your project best.

![ContactZilla.com](http://github.com/simpleweb/jQuery-Multi-Row-Input/raw/master/contactzilla.png)