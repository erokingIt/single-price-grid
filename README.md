# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./images/Screenshot_Desktop.png)

![](./images/Screenshot_mobile.png)

### Links

- Solution URL: https://github.com/erokingIt/single-price-grid
- Live Site URL: https://erokingit.github.io/single-price-grid/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Used paint.net to determine component colors, dimensions, and padding/margins

### What I learned

Learned how to use css grid statically and in a responsive layout. 
After some trial and error I learned to put the shadow box on the grid-container to work in a responsive layout.

```css
  /* The grid container */
  .grid-container {
    display: grid;
    grid-template-areas: 
      'header header' 
      'left right';
    /* grid-column-gap: 10px; - if you want gap between the columns */
    
    max-width: 624px;
    box-shadow: 0px 0px 20px 0px hsl(218, 22%, 67%);
    border-radius: 12px;
  }
```

### Continued development

I'd like to use css grid more and tryout other methods for grid layouts.

### Useful resources

- (https://www.w3schools.com/) - Helped me gain understanding of grids, transparent rounded corners, and box shadows.

## Author

- Website - (https://github.com/erokingIt)
- Frontend Mentor - (https://www.frontendmentor.io/profile/erokingIt)
