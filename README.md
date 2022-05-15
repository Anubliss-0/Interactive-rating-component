# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Links

- Solution URL: [https://github.com/Anubliss-0/skilled-elearning-page]
- Live Site URL: [https://anubliss-0.github.io/Interactive-rating-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Javascript!

### What I learned

This was my first project using JavaScript. It wasnt easy but I am happy with the results!

```js
function setScore() {
  score = this.value;
  score = parseInt(score);
  console.log(`The score is now ${score}`);
  buttons.forEach((button) => {
    button.classList.remove(`orange`);
  });
  this.classList.add(`orange`);
}

function submit() {
  fadeOut();
  setTimeout(dispNone, 300);
  setTimeout(insertContent, 500);
  setTimeout(fadeIn, 600);
}
```

### Continued development

The plan now is to use more Javascript.

## Acknowledgments

Big up Wes Bos.
