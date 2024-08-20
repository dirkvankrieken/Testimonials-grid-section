# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/dirkvankrieken/Testimonials-grid-section](https://github.com/dirkvankrieken/Testimonials-grid-section)
- Live Site URL: [https://dirkvankrieken.github.com/Testimonials-grid-section](https://dirkvankrieken.github.com/Testimonials-grid-section)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

## What I learned

- to set a background image to no-repeat and set it's location within the parent containing element.
```
.card-1 {
	background-image: url('images/bg-pattern-quotation.svg');
	background-repeat: no-repeat;
	background-position: top 0 right 30px;
}	
```
- to set up a grid with CSS grid and to determine the size and place of elements within the grid
```
.card-container {
	display: grid;
	grid-template-columns: repeat(4, 1fr);
	grid-auto-rows: minmax(100px, auto);
	grid-template-areas:
	"card-1 card-1 card-2 card-5"
	"card-3 card-4 card-4 card-5"  
   }
```

### Useful resources

- [https://www.w3.org/TR/css3-grid-layout/](https://www.w3.org/TR/css3-grid-layout/)

## Author

- Website - [dirkvankrieken.com](https://dirkvankrieken.com)
- Frontend Mentor - [@dirkvankrieken](https://www.frontendmentor.io/profile/dirkvankrieken)
