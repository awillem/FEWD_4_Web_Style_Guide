**Project 4 - Treehouse Front End Web Deveopment Techdegree**    
***Web Style Guide***

In this project, we were given the html and css files for a web style guide. Our directions were to change over the css to sass and have the final page with sass looking just as the example files looked with only css.  The changes included creating partials for base, components, and utilities, as well as variables and mixins.  

The original html and css can be used to see what the project should look like.  They are included inside the resources folder 

***Exceeds Expectations***
* create a mixin that excepts a breakpoint as a parameter.  The mixin should create a media query with a min-width breakpoint.
  * use this media query mixin for all media queries. I used this mixin with the buttons, grid, and navigation.
* use at least 1 nested selector that use the '&' to append a child class selector to the base.  I used this within the navigation for the .nav-link and .nav-link:hover selectors.  
* create a hover effect for buttons, using the lighten color function at 15% and a transition so the changes fade in. This change is part of the mixin that creates the styles for the buttons using the different color classes, like .info.  I also made a change to the text, making it darker on hover

***Other Changes***
* I also created two other mixins.  
  * For the first one, I stored the 5 colors for default, success, info, warning, and error in a map.  The mixin 'types' takes in that map, and iterates over them, creating both the background-color, and then the hover effects. 
  * The other mixin is for flex layout.  It sets the display to flex, and has an option parameter $dir to set the flex-direction.  