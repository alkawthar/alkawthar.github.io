## Website Performance Optimization portfolio project

Instructions:

To view the portfolio website:

Either go to https://alkawthar.github.io/

Or download the ZIP file:

Click download ZIP on the right of the screen, then extract the zip file to your computer.

Navigate to where you unzipped the file.

Double-click index.html to open the portfolio page in your browser.

Navigate to views folder then double-click pizza.html to open the pizza page in your browser.


Optimizations in Pizza Site to Increase the Frame-rate to 60 fps When Scrolling:

Changed all instances of "querySelector" to "getElementById" or "getElementsByClassName" depending on whether a class or id is needed.

Major changes were made to "updatePositions" function which moves the sliding background pizzas based on scroll position.

Moved "scrollTop" declaration outside the loop to improve performance.


Optimizations in Pizza Site to Resize Pizzas is Less Than 5 ms Using the Pizza Size Slider:

Changed all instances of "querySelector" to "getElementById" or "getElementsByClassName" depending on whether a class or id is needed.

Major changes were made to "changePizzaSizes" function which iterates through pizza elements on the page and changes their widths.

Determine the value of "newWidth" variable outside the loop to improve performance.

Assign the value of "randomPizzas" outside the loop to increase performance.
