ISSUE:
IE11 renders the div in header containing the phone number and donate button differently than current versions of Firefox, Chrome and Safari browsers. IE11 places the donate button on the same line as the phone number (should be below it), which causes a secondary issue with the nav container overlapping the logo.

CSS HACK TO FIX:
If you take a look at the nami.css file at lines 252-256, this is the hack syntax added to get the result I'm looking for in IE11. If you take these lines out of the CSS file, you'll see the display issue in IE11.  
