# Supersimple.dev button exercise

This is a solution to the [Supersimple.dev Lesson 2 Exercise - CSS Basics](https://youtu.be/G3e-cpL7ofc) at the @44:22 mark.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Acknowledgments](#acknowledgments)

## Overview
Goal of this exercise to recreate popular social media buttons as accurately as possible without viewing web tools or existing solutions. 

### The challenge
Recreate button appearance with hover and action states. 

### Screenshot

![](./screenshot.jpg)

### Links
- Live Site URL: https://oliviachan-dev.github.io/social-media-buttons/
Link will contain my solution to this exercise. 

## My process
My general process was creating the HTML element, then styling the button by color, font, border. Finally, I added hover and active states.

### Built with
- Semantic HTML5 markup
- CSS custom properties

### What I learned
Something new I learned was how to add simple transitions to buttons.  

```css
.button-transition {
  transition: opacity 0.15s;
}
```
Something I would like to incorporate in the future are box-shadows. When I looked at the buttons from Uber, Amazon, GitHub, Bootstrap, and LinkedIn however, they did not use shadows. Perhaps shadows on buttons are an outdated design choice?

## Acknowledgments
Thank you to SuperSimpleDev for creating interesting and practical web development exercises and solutions! :)

Also thanks to HTML&CSS by Jon Duckett for teaching me the basics of html and css :)
