jawshackme
==========

FontAwesome en Jaws-Project 1.1.1

From https://github.com/josh18/TinyMCE-FontAwesome-Plugin


###modify: TinyMCE.php Layout.html layout.html

````
./include/Jaws/Widgets/TinyMCE.php
adding: span at end

'iframe[class|id|marginheight|marginwidth|align|frameborder=0|scrolling|align|name|src|height|width|span]';

./gadgets/ControlPanel/Templates/Layout.html

adding:

<link href="http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.min.css" rel="stylesheet" type="text/css">

./data/themes/gray/layout.html

adding:

<link href="http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.min.css" rel="stylesheet" type="text/css">

seen 09/05/15
````
