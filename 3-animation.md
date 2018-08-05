# Part 3: Basic building blocks of animation with JavaScript 

Let's take the shapes we've drawn using the [**p5js library**](https://p5js.org/) and write a bit more code to animate them!

<br/>

:books: **To learn more about p5js:**

  - [Official p5js "Getting Started" guide](https://p5js.org/get-started/)
  - [Full reference manual](https://p5js.org/reference/) about all the p5js functions

<br/>

<hr/>

## Challenge 1:

Take the code you wrote to generate shapes in random colors and locations, and ***move it into the draw()*** function (which is at the bottom of the `script.js` file).

How did this change your app? Take a look and experiment with some other small changes to your code.

<br/>

**Bonus:** Try also using a random number for the size of your shapes!

**Bonus for those with some programming experience:** Create not just one or two, but ***one hundred*** random shapes that get redrawn on every frame of the animation!

<br/>

## Challenge 2:

Notice that in your animation, the shapes drawn in previous frames are still visible. In fact, if you let the animation run long enough, or if you're creating lots of shapes on every frame, you'll notice that they will end up overlapping each other!

**Your challenge:** Use the p5js `clear()` function as the very first line inside the `draw()` function, to clear the screen before each animation frame is drawn.

  > **Note:** The `clear()` function does not take any inputs, so you literally type `clear();` with nothing inside the parentheses!

<br/>

How did that change the look of your animation?

<br/>

**Bonus:** Make a prediction *before* you run the code: what will happen if you run the `clear()` function ***after*** the functions that draw your shapes? After discussing your thoughts, try it to see what happens!

<br/>

## Challenge 3:

The p5js library also provides a simplified way to access the user's mouse coordinates, for easy prototyping of interactive animations!

**Your challenge:** For any of the numbers (or variables that contain numbers) being used to control your shapes, ***replace one*** with `mouseX` -- this is a variable that p5js defines for us, which contains the current X coordinate of the user's mouse.

For example:
```javascript
// Be sure to put this code inside the draw() function
// The first input of the rect() function below uses mouseX; all the other inputs will stay the same
rect(mouseX, 300, 50, 100);
```

<br/>

## Challenge 3:

Can you guess what the p5js variable for the current Y coordinate of the user's mouse is? Try it!

**Your challenge:** Make one of your shapes move exactly to wherever your mouse cursor is, using both of the provided mouse coordinate variables!

<br/>

## Challenge 4:

Time for some more experimentation! What would happen if you used the user's mouse coordinates as the value for something else -- the width or height of the shape? The color of the shape? Something else? Try it!

<br/>

## Challenge 5:

For these next challenges, we'll use a new Glitch project template:

<br/>

:star: [**Click here to open the next template project for another animation example**](https://glitch.com/edit/#!/canvas-animation) :star:

Then be sure to remix it so you'll have your own copy that you can edit!

<br/>

**Your challenge:** Take a look inside the new Glitch template project you just remixed, and look in the `script.js` file again to see our new JavaScript example code.

***Before anything else***, look at the code at take a guess as to what it will do!

Then ***discuss*** your ideas -- and last but not least, then open the live page to see what it does.

<br/>

## Challenge 6:

First, ***discuss:*** which part of the code controls the speed of the animation? 

Then ***change*** one tiny part of the code to make the animation ***slower***, and then change it again to make it ***faster***.

<br/>

## Challenge 7:

Change the code a little bit so the square will move ***vertically***, from the top of the screen down to the bottom.

  > **Hint:** You may want to review what those four numbers in the `rect()` function each stand for. Which of those four numbers is replaced by a variable in our example code?

<br/>

## Challenge 8:

Change the code a little bit more to make the square move ***diagonally***, from the top-left corner of the canvas across to the bottom-right corner.

<br/>

## Challenge 9:

Create **two** (or more) different shapes of different colors that all move around the screen!

<br/>

## Bonus Challenge:

What if you want your animated shape to ***stop*** at the edge of the screen -- for example, if you're making a game like Tetris or Snake?

<br/>

Start working on this problem in stages:

  1. What are the coordinates required to draw a square in the top-right corner of the screen?
  
  2. Draw a diagram illustrating the coordinates of a square that's ***not*** at the edge of the canvas, and another diagram illustrating a square that ***is*** beyond the edge of the canvas.
  
  3. How would you describe those two scenarios with an equation? (You'll only need to use addition and/or subtraction.)
  
  4. Once you've solved the problem on paper, you'll need to learn more about JavaScript to implement your solution -- one key word to learn about is ***conditional statements*** to check whether a condition is true or not.
  
This is a tricky one for beginners, so save this one for later -- as you learn more about programming, you'll be ready to return to this challenge again in the future!
  

<br/>
<hr/>

### :point_right: **Next up: [click here to go to the next set of challenges!](#)**

