#Installation instructions.

# Introduction #

  1. Copy the files to suitable directories
  1. Edit the config files


# Details #

> Simply copy the ozbas.html and the .js files to a directory accessable via the webserver
> Copy the ozbasJSON.cgi and SL\_connect.py file to a cgi-bin directory

> Edit SL\_connect.py - configure with the postgresql db username
> Edit ozbas-config.js - update the cgi path if required

> Apologies - Edit ozbas.html search for the yui script includes and replace /yui260/ with


Be sure to leave the rest of the line intact e.g

Change



&lt;script type="text/javascript" src="/yui260/utilities/utilities.js"&gt;



&lt;/script&gt;



to



&lt;script type="text/javascript" src="http://yui.yahooapis.com/2.6.0/build/utilities/utilities.js"&gt;



&lt;/script&gt;



do this for the 10 or so css and javascript includes