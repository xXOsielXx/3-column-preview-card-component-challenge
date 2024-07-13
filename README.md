# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: https://www.frontendmentor.io/solutions/3-column-preview-card-component-with-sass-9-z7QcfOA4
- Live Site URL: https://xxosielxx.github.io/3-column-preview-card-component-challenge

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- [SASS](https://sass-lang.com/) - Styles lenguage

### What I learned

I was stuck with the buttons, they were taking up the entire width. This happened because the buttons are children of a flex container with `flex-direction: column`, and apparently the default value of align-self is stretch. So I gave it a `align-self: flex-start` and it solved

In the other hand, in this project I used the clamp function

```sass
.preview-card-component &gt; section
  width: clamp(308px, 80%, 440px)
```

### Useful resources

- [Perplexity](https://www.perplexity.ai/) - This is a great tool for online search purposes. Thanks to this AI I have been able to find the solution to my code problems very quickly.
- [Stackoverflow](https://stackoverflow.com/) - This is an excelent way to search for solutions. In this popular website I finded solutions to my code problems many times because I'm never the first to have a specific problem appear.

## Author

- Website - [Osiel Hernández](https://xxosielxx.github.io/osez-folio)
- LinkedIn - [Osiel Hernández](https://www.linkedin.com/in/osiel-hern%C3%A1ndez-rodr%C3%ADguez-9869612a1/)
- Github - [@xXOsielXx](https://github.com/xXOsielXx)
- Frontend Mentor - [@xXOsielXx](https://www.frontendmentor.io/profile/xXOsielXx)