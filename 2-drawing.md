# Part 2: Intro to drawing with JavaScript 

We'll be working in pairs to tinker with more code, using functions provided by awesome [**p5js library**](https://p5js.org/) designed to making coding more accessible for beginners, especially for artists who want to make creative works with code.

<br/>

:books: **To learn more about p5js:**

  - [Official p5js "Getting Started" guide](https://p5js.org/get-started/)
  - [Full reference manual](https://p5js.org/reference/) about all the p5js functions

<br/>

<hr/>

## How to use Glitch for our next challenges:

<br/>

:star: [**Click here to open a template project with p5js already set up**](https://glitch.com/edit/#!/canvas-challenges) :star:

<br/>

**Instructions:**

  1. Save your own personal copy of the template project by clicking the project's name in the top left corner, and then click "Remix This" in the dropdown menu to make your own personal copy.
  
  2. It will load the page again, and generate a name made of *two random words*. This is your own personal copy that nobody else can edit.
  
  3. **To see the live app and test it out**, click "Show Live" on the top left and it'll open the web page in another tab.

![glitchscreenshot](https://user-images.githubusercontent.com/1555022/40146036-e95ba9ec-5918-11e8-9533-094d6f8d858e.png)

<br/>

## Challenge 1:

Copy the example code below and paste it right after where it says to "write your code here" inside a JavaScript comment (comments start with `//` and are ignored by the computer). 

```javascript
rect(200, 300, 50, 100);
```

Then try ***changing*** those four numbers that draw the rectangle, and ***identify*** what they all do!

<br/>

  > Be sure to click **"Show Live"** at the top left of the page to open your live web page and see your amazing rectangle!

<br/>

## Challenge 2

Take a closer look at the `createCanvas()` function that we're using . ***Change*** the two numbers and ***identify*** what they both do.

Again, remember to check the live web page each time you change the numbers to see what happens!


<br/>

## Challenge 3:

Draw a circle using the `ellipse()` function -- see [the p5js reference page for ellipses](https://p5js.org/reference/#/p5/ellipse) and feel free to copy code examples from there!

<br/>

## Challenge 4:

Let's do this challenge in a few separate steps:

  1. Before anything else, put your heads together and discuss what you know so far about the coordinate system we've been using with drawing these shapes.
  
  2. Take a guess as to what the coordinates are for the ***top left corner*** of the canvas. For each of your guesses, discuss **why*** you think that might be the case.
  
  3. Finally, ***change*** your code so that your circle will appear in the top left corner of the page.
  
  4. Did it work? Why or why not? (And did you learn something from this experiment?)

<br/>

## Challenge 5:

Draw a circle ***exactly in the center of the canvas***.

  > **Hint:** You'll need to take a look at the numbers used for our `createCanvas()` function, and do a little bit of  arithmetic to find the coordinates that you need.

<br/>

## Challenge 6:

Look at [the reference page for the `fill()` function](https://p5js.org/reference/#/p5/fill) and use it to draw ***two*** separate shapes, using ***two different colors*** for each one.


<br/>

## Challenge 7:

First, ***take a guess*** as to what will happen when we run the example code below. ***Discuss*** your ideas!

After you've made predictions and discussed them, copy-paste the code into your own project and see what happens:

```javascript
let squareWidth = 75;
rect(400, 350, squareWidth, squareWidth);
```

<br/>

## Challenge 8:

Write two more lines of code to create two more variables, one for each coordinate that determines where the square will be drawn on the canvas. Assign a number between 0 and 500 to each of your two variables, mirroring the example:

```javascript
let squareWidth = 75;
// Write two more lines of code below to create the variables for xPos and yPos


rect(xPos, yPos, squareWidth, squareWidth);
```

<br/>

## Challenge 9:

Let's spice things up with a little *randomness*! Take a look at [the p5js reference page for the `random()` function](https://p5js.org/reference/#/p5/random) to learn more about how it works.

```javascript
// Example 1 -- You can save the random number to a variable, then use that variable in your shape!
let randomNum1 = random(200);
rect(randomNum1, 300, 75, 75);

// Example 2 -- Or you can put the random() function directly inside your shape-drawing function:
rect(random(200), 300, 75, 75);
```

<br/>

**Your challenge:** Combine the p5js random number generator function with your code from challenge #3 above to draw a square at a ***random*** location (with randomized coordinates)!

Once you get it working, be sure to refresh the page a couple times to confirm that its location is indeed random!

<br/>

## Challenge 10:

Combining what you find in the reference pages for the p5js `fill()` function and the `random()` function, give one of your shapes a ***random color***!

Again, be sure to refresh the page to confirm that the color is indeed random. :)

<br/>
<hr/>

### :point_right: **Next up: [click here to go to the next set of challenges!](https://github.com/LearnTeachCode/js-intro-creative-coding/blob/master/3-animation.md)**

We'll take our simple shapes and start moving them across the screen, our first intro to animating with code!
