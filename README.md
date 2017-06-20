## Website Performance Optimization portfolio project

To successfully run the application download the files and use a compatible browser, IE, Chrome, etc.

index.html
- Inlined all applicable css to the <head> in it's own <style> tag. 
	- optimized via https://jonassebastianohlsson.com/criticalpathcssgenerator/
  - https://developers.google.com/speed/docs/insights/OptimizeCSSDelivery
- Optimised, resized pizzeria.jpg
- Added media="print" to the print.css


For pizza.html
views/js/main.js 
- Created a container to hold the pizza objects so that there was no need to rebuild 
  each time in the for loops.
- Reduced pizza count for the sliding action. 
- Instantiated Var elem = "" outside of second for loop



