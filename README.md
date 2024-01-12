# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here]([https://your-solution-url.com](https://www.frontendmentor.io/solutions/blog-preview-card-using-html-css-cUJXIObK-s))
- Live Site URL: [Add live site URL here](https://azpenmeadows.github.io/fm-blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to use clamp() to auto resize context based on screen size without the need for @media queries


```css
body {
    margin: 0;
    padding: 0;
    font-family: 'Figtree', sans-serif;
    color: var(--color-neutral-black);
    background-color: var(--color-primary);
    font-weight: var(--ft-weight-normal);
    font-size: clamp(0.8rem, 1.5vw, 1rem);
}
```

### Continued development

I would like to learn a litte more about auto resizing elemants based on screen size. The solution I have resized my paragraph text as needed, but both the height and width of card get smaller on mobile screens, rather than width changing and height staying the same as per the mobile design image.

### Useful resources

- [Microsoft Copilot](bing.com) - help me search for solutions for resizing text without @media. Suggested I try clamp() and setting font size with vw.
- [MDN Web Docs]([https://www.example.com](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp)) - Used this to learn more about clamp() in CSS

## Author

- Github - [AzpenMeadows]([https://www.your-site.com](https://github.com/AzpenMeadows))
- Frontend Mentor - [@AzpenMeadows](https://www.frontendmentor.io/profile/AzpenMeadows)
