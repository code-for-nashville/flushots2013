DEPRECATED

This project is no longer being actively maintained by Code for Nashville. https://vaccinefinder.org/ is an excellent, maintained, national alternative run with help from the department of Health and Human Services.

----


I have again partnered with the Chicago Department of Public Health (CDPH) to create an updated flu shot finder web application. Currently it has all the CDPH free locations and events. It also includes Walgreens, Dominick's, Jewel/Osco, and CVS locations that offer flu shots.

I created this as a volunteer effort. The code that runs it is open, completely free, and reusable by anyone.

Special thanks to Smart Chicago Collaborative for hosting this thing. Also thanks to Raed Mansour, Dr. Julie Morita, and Commissioner Dr. Bechara Choucair (all with CDPH) for being great to work with.

NOTES:

-- This a HTML/CSS/JavaScript web application. It does have one small PHP file to construct an iCal file for users who want a calendar reminder of one-off events. This PHP file should be simple enough to rewrite in whatever server-side language is available in your environment.

-- I used the generic Bootstrap 3 download, except it has one modified LESS variable: '@screen-sm' was set to '860px'.

-- If you want to reuse this code for your city/county/province/state, a good place to start is in main.js and altering the properties of the "Default" object at the top of the file.

-- I try to use meaningful variable names, so hopefully the code won't be too hard to follow.

-- The data behind this site is a Google Fusion Table and is found here: https://www.google.com/fusiontables/DataSource?docid=1leqPq9hrsGhnE8NoT00YZn1ITTzhK6BhrF8LNL4
