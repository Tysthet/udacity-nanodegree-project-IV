##4th project for Udacity's Front-end Web Developer Nanodegree
###Website Optimization

####Objectives:
  - For index.html : achieve a PageSpeed rank of 90 or above.
  - For pizza.html : achive a framerate of 60 fps on scrolling and a time to resize pizzas lower than 5ms.

Each optimization is detailed inside the comments.
Here is an overview of the modifications in main.js.

####GENERAL
  Replaced document.querySelectorAll() by document.getElementsByClassName().
  Moved pizzasDiv variable declaration outside of a for loop.

####In changePizzaSizes()
  Created variables to reduce the amount of calculations in the for loop.

####In updatePositions()
  Created a variable to reduce the amount of calculations in the for loop.

####When the DOM content is loaded
  Reduced the number of iterations, i.e. the number of pizzas on screen, to 35.