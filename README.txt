to include the JQuery library, popper.js library and Bootstrap's Javascript plugins. Bootstrap by default uses the JQuery Javascript library for its Javascript plugins. Hence the need to include JQuery library in the web page.
Responsive feature is built in Bootstrap
Bootstrap grid usese CSS flexbox layout as standard
5 Bootstrap Classes: default, sm, md, lg, xl
5 Bootstrap screen sizes: Extra small, Small, Medium, Large, Extra Large
Bootstrap column classes: col-, col-sm-, col-md-, col-lg-, col-xl-,
eg <div class = "col-12 col-sm-5"> content takes all 12 cols when the screen is xs, takes 5 cols when the screen is sm and beyond
"order- " classes, re-order the content on the screen. eg. <div class = "col-sm-5 order-sm-last"> the div will be on the rightmost side on sm or beyond screen
 <div class = "col-sm-5 order-sm-7"> order the div 7th on the screen from left to right
<div class = "col-auto"> occupied cols determined by the content
<div class = "col-sm-4 offset-sm-1"> offset the 4 col div to right by one column
custom css overrides Bootstrap CSS
