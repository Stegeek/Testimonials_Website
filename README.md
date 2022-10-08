# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot
screenshot.png

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/css-grid-and-css-flexbox-J3hZAYWBOj)
- Live Site URL: (https://splendid-treacle-9b26fd.netlify.app/)
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learnt how to use CSS grid to make grid areas span over some columns and rows. 
There are two ways to do this; by using grid-areas or by using grid-column and grid-row.
Below I used the grid-column and grid-row method.

```html
<div class="container">
        <div class="daniel"></div>
</div>
```
```css
.container {
    display: grid;
}

.daniel {
    grid-column: 1 / 3;
    grid-row: 1;
}

```

### Useful resources

-  [Resource 1](https://www.youtube.com/watch?v=0xMQfnTU6oo&t=11s) - This helped me with the advanced knowledge of the CSS-grids. I really liked this pattern and will use it going forward.
- [Resource 2](https://freecodecamp.org) - This is an amazing website which helped me with introduction to CSS-grids by building a project. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [Stephen Gachoki](https://www.frontendmentor.io/profile/Stegeek)
- Twitter - [@Steve_thedev](https://twitter.com/Steve_thedev)

