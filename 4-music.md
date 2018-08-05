# Part 4: Basic building blocks of creating music with JavaScript 

Let's get our feet wet with a quick look at the [**p5js SOUND library**](https://p5js.org/reference/#/libraries/p5.sound) to make some music (or noise)!

<br/>

:books: **To learn more about p5js:**

  - [Official p5js "Getting Started" guide](https://p5js.org/get-started/)
  - [Full reference manual](https://p5js.org/reference/) about all the p5js functions
  - [p5js sound library reference page](https://p5js.org/reference/#/libraries/p5.sound)

<br/>

<hr/>

## Check your speaker volume! Not too loud!

Our computers are going to be making noises, so be careful -- if you make a typo to accidentally set the amplitude too high (for example), it might not be so nice for all of our ears! So ***turn on your computer's sound, but keep it low.***

<br/>

## Challenge 1:

The p5js sound library provides an easy way to load and play sound files. Combining this with the p5js functions to detect key presses, combined with the building blocks of JavaScript, we can make our own drum kit!

⭐️ [Click here to open this other example, and make your own remix of it!](https://glitch.com/edit/#!/p5js-sound3) ⭐️

<br/>

The audio files are borrowed from [this open-source drum machine web app](https://github.com/siggy/beatboxer), and you can [play the demo here](https://sig.gy/beatboxer/)!

**Easy challenge:** Try out the other sounds by replacing `snare_drum.wav` at the end of the file URL with the name of one of the other sound files listed here: https://github.com/siggy/beatboxer/tree/master/sounds

<br/>

**More interesting challenge:** Build out this virtual drum kit by creating more variables, loading more sound files, and adding onto the if/else if statement to play different sounds depending on which keys the user presses on their keyboard!

<br/>

## Challenge 2:

Next, take a look at this next example -- again, ***before*** you run the app, look at the code and make a prediction about what you think it'll do.

⭐️ [Click here to open this other example, and make your own remix of it!](https://glitch.com/edit/#!/p5js-sound2) ⭐️

**Your challenge:** How would you combine that working code with the `fill()` function to also change the color of the circle based on the user's input?


<br/>

## Challenge 3:

All modern web browsers have a built-in Web Audio API, which allows your web browser to essentially be a synthesizer! You can generate your own sounds from the building blocks of frequency, amplituded, and different types of sound waves!

⭐️ [Click here to open this sound synthesizing example, and make your own remix of it!](https://glitch.com/edit/#!/p5js-sound1) ⭐️

**Before you run the app**, look at the code for the example above and discuss what you think you'll hear!

<br/>

## Challenge 4:

Take a look at the [p5js setType() function for oscillators](https://p5js.org/reference/#/p5.Oscillator/setType) and modify the code in the example project to try out all the different types of sound waves!

How does each one sound, compared to the others? Which one do you like the best?

  > These might not sound so pretty on their own, but you can make more interesting sounds (say, to mimic the sound of a guitar or drums) by combining of various types of sound waves at different frequencies!

<br/>

## Challenge 5:

Change the frequency of the sound to make it higher or lower, using the [p5js freq() function](https://p5js.org/reference/#/p5.Oscillator/freq). Take a look at [the reference page](https://p5js.org/reference/#/p5.Oscillator/freq) to learn more about it!

<br/>

## Challenge 6:

We can use the [p5js map() function](https://p5js.org/reference/#/p5/map) to remap a number from one range to another, and use this trick to convert a user's mouse coordinates into a range that can work for frequencies of sound waves!

Copy the following code snippet into the draw() function and see what happens to your app now:

```javascript
// NOTE: the width and height variables provided by p5js refer to the width/height of the drawing canvas

// Map the mouse X coordinate to a number between 40 and 880
let freq = map(mouseX, 0, width, 40, 880);
osc.freq(freq);

// Map the mouse Y coordinate to a number between 1 and 0.01 
let amp = map(mouseY, 0, height, 1, .01);
osc.amp(amp);
```

**Your challenge:** Can you combine the code above with snippets from your drawing/animation code so that as the mouse moves, shapes and/or colors also change accordingly on the screen to go along with the beautiful music you're creaing? :)


<br/>
<hr/>

:trophy:* Congrats!!! That's it for this workshop, but you have enough building blocks now to start making some creative experiments of your own! Go forth and make (and break) some more code, and never stop learning! :)
