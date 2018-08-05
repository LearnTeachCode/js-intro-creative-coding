# Part 3: Basic building blocks of animation with JavaScript 

Let's take the shapes we've drawn using the [**p5js library**](https://p5js.org/) and write a bit more code to animate them!

<br/>

:books: **To learn more about p5js:**

  - [Official p5js "Getting Started" guide](https://p5js.org/get-started/)
  - [Full reference manual](https://p5js.org/reference/) about all the p5js functions

<br/>

<hr/>

## New template project:

<br/>

:star: [**Click here to open a NEW template project for animation examples**](https://glitch.com/edit/#!/canvas-animation) :star:

<br/>

**Instructions (recap):**

  1. Save your own personal copy of the template project by clicking the project's name in the top left corner, and then click "Remix This" in the dropdown menu to make your own personal copy.
  
  2. It will load the page again, and generate a name made of *two random words*. This is your own personal copy that nobody else can edit.
  
  3. **To see the live app and test it out**, click "Show Live" on the top left and it'll open the web page in another tab.


<br/>

## Challenge 1:

Take a look inside the new Glitch template project you just remixed, and look in the `script.js` file again to see our new JavaScript example code.

***Before anything else***, look at the code at take a guess as to what it will do!

Then ***discuss*** your ideas and, last but not least, open the live page to see what it does.

<br/>

## Challenge 2:

First, ***discuss:*** which part of the code controls the speed of the animation? 

Then ***change*** one tiny part of the code to make the animation ***slower***, and then change it again to make it ***faster***.


<br/>

## Challenge 3:

So, what if we want just *one individual square* to move across the screen, instead of painting a line across the screen? Luckily, p5js has a function for that names `clear()`, which erases the entire canvas so you can start over with a clean slate.

**Write `clear();` right *above* of the example code**, around line 25 or so. Test it to make sure it works!

  > **Hint:** You only need to type, literally: `clear();` and it should work. If it doesn't, double-check *where* in the code you put it.
  
 
<br/>

## Challenge 4:

**Take a guess and discuss:**

  1. Does it matter where/when we use the `clear()` function?
  
  2. Why or why not?
  
  3. Make a specific prediction: what do you think will happen if we move the `clear()` function to run *after* our example code instead of before it?
  
  4. Finally, test your prediction!

<br/>

## Challenge 5:

Change the code a little bit so the square will move ***vertically***, from the top of the screen down to the bottom.

  > **Hint:** You may want to review what those four numbers in the `rect()` function each stand for. Which of those four numbers is replaced by a variable in our example code?

<br/>

## Challenge 6:

Change the code a little bit more to make the square move ***diagonally***, from the top-left corner of the canvas across to the bottom-right corner.

<br/>

## Challenge 7:

Here's another cool trick: p5js makes it easy for us to access where the user is clicking their mouse -- they provide two variables named `mouseX` and `mouseY` to represent the coordinates of where your mouse is on the canvas!

First, copy-paste the code below somewhere above or below the example animation code. Second, **delete** the numbers for the x and y coordinate and **replace** them with `mouseX` and `mouseY`:

```javascript
fill("purple");
// Replace the appropriate numbers with the mouse coordinate variables:
ellipse(250, 350, 80, 80);
```

Test it out! You should see e a purple circle follow your mouse around the canvas!

<br/>

## Challenge 8:

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

