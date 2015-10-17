* If you have 5 different stylesheets, how would you best integrate them into the site?

First I would be using SASS for my stylesheet needs and I would have one SASS file called main or something similar that would load in my 5 partials SASS files and that main SASS file loading would take care of integrating all 5 different stylesheets (which are now SASS partials or modules)