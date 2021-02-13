# figure-of-the-day

This task will build upon the objects you created in the previous session, so if you haven't done so, complete those now.

1. Create an HTML file. Within that, create a button. The label should say "Get a random hero".

2. Create a JS file. Within, create a listener so that you are able to know when the button was pressed.


3.  Create a function that will return the middle most hero in your list of heroes. So, if you have 4 heroes on your list (the minimum), it should return the second or third person(you can pick which).


4. Now that you can confirm that the button click works, make it so that when the button is clicked, the function you created in step 3 is called, and displays the information on the page. Style the information so it's presentable.
   

5. Instead of returning the same hero each time, could we return a random hero? to do so, we need a couple of things:
   1. We need to use another function-this time from JS's Math library. `Math.random()` will give us a random number between and 0 and 0.9. That's great, but we'll need whole numbers. Let's multiply it by the number of our heroes: `Math.random()*<number of heroes>` 
   
   The math library also has a handy function called floor which will make the number even nicer, so we can combine this to create `Math.floor(Math.random()*<number of heroes)`. Console log this information out to see what numbers are generated.

   2. Now implement this new way where you get the second person in your list. Refresh your page and confirm that you can now show different heroes when you click on the button.




[ ] I have completed this task