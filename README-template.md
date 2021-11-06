# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![Final Desktop View](/final/desktop-view.JPG.jpg)
![Final Mobile View](/final/mobile-view.JPG)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

CSS Grid - using grid-templates-columns and setting each section using the grid-column style. 


```css

main {
        grid-template-columns: 1fr 1.5fr;
        text-align: left;
    }

    h1 {
        margin: 0;
    }

    /* grid layout */
    .intro {
        grid-column: 1/2;
    }

    .reviews {
        grid-column: 2/3;
        align-self:center;
    }

    .quotes {
        grid-column: 1/-1;
    }

```

## Author

- Website - [Michbot](https://github.com/michb0t)
- Frontend Mentor - [@michb0t](https://www.frontendmentor.io/profile/michb0t)
- Twitter - [@michbot7](https://twitter.com/michbot7)

