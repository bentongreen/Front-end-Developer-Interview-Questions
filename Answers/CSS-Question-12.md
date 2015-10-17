* What are the different ways to visually hide content (and make it available only for screen readers)?

There are a number of ways to hide content but display:none and visibility:hidden are a separate concept and part of making content completely hidden.
The classic way to hide things was to use a hidden class (.hidden) and maybe make things with that class a few thousand pixels off screen but this method can have a number of problems. A newer method of hiding content is with the CSS 2.1 clip property and setting its values to 0 will make the content invisible.

Source: (http://www.sitepoint.com/when-and-how-to-visually-hide-content/)