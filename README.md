# PC06-Funcy-Animation
### In this repo
1. **img2gif.py** - Python turtle only works with .gif files. (Changing the extension or converting it in Adobe won't work.) To use this tool, download and place the file in the same folder as the image of choice. Read the code description carefully, and interact with the code in the command line console.
2. **start_code.py** - Start code with commented sections to help your code organization. There are also some key changes to turtle! Including: <br>
    `turtle.tracer(0)` this command turns off turtle's built-in animation, but requires the panel to be updated manually.<br>
    `panel.update()` this command updates the information sent to draw on the panel. This should be called at the end of a frame drawing (end of while loop block)<br>
    `running = True` this boolean variable is used to control the animation loop. To have stop conditions, you should use a conditional statement inside of the loop to change the value of running from `True` to `False`.
3. **wrapAroundBoundary.py** - Example code demonstrating how while loops are used to make animations, how conditional statements can be used for edge detection.

## PC06 Assignment Description & Notes
We're starting to move toward task-oriented programming--making code that uses almost entirely functions to execute a task. This will help us build toward Object Oriented Programming (OOP) which is the culmination of this course's learning goals. Scary, right? #hallowee!

**Protips**: 
- Consider using code you've already created in this class. Build the pattern from PC03 or reuse the code from PC04 to make a cool pattern that moves or has some fun behavior. <br>
- Behaviors do not have to be repetitive! They can wiggle, bounce, spin, get bigger or smaller, hide behind objects...
- Image/object collision is **HARD** Keep it simple and plan to build on it as you learn!

As you are expending your skillset, you should consider looking to see if the solution you need exists already. Use search engines to search for:<br>
    `python turtle` plus whatever the rest of your description is.<br>
This means you'll get practice articulating and describing what you want your code to do!

### Remember to cite code and use no more than 20% of borrowed code
`# code modified from <URL>`<br>
`# code borrowed from <URL>`

There is also a repository of useful code for you to use. The 20% limit does not apply to this code, **but you must cite it**. Check back frequently, as it will regularly be updated (based on student requests)!

## Requirements
Your assignment must: <br>
    1. Have one unique function that is both defined and called. (Please don't borrow a function if you can help it...the point is practice.)<br>
    2. At least one function must be called within the animation loop (while loop) <br>
    3. **Include any images you used in your code!**
    
### Extra Credit (Grads must complete 2)
    - 0.5 pts - use an image for the turtle shape
    - 0.5 pts - have a conditional statement that stops the while loop (change the value of the variable `running` to `False`)
    - 1 pts - create a function that returns a boolean for any edge detection (remember descriptive naming!)

## Submit to this repository:
    - MP04 - your edited version of wrapAroundBoundary.py
    - PC06 - your pseudocode for your animation
    - PC06 - your script (.py file)
    - PC06 - any images you used in your code!
    
### MP04 Due Fri
### PC06 Pseudocode Due Sun
### PC06 Due Weds
