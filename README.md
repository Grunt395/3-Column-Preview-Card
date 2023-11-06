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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![screenshot](./3%20Column%20Preview%20Screenshot.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/3-column-preview-card-with-html-and-css--G3OwL6Plu](https://www.frontendmentor.io/solutions/3-column-preview-card-with-html-and-css--G3OwL6Plu)
- Live Site URL: [https://grunt395.github.io/3-Column-Preview-Card/](https://grunt395.github.io/3-Column-Preview-Card/)

## My process

### Built with

- HTML5 markup
- CSS Properties
- Flexbox

### What I learned

I Learned how to use classes to affect multiple components simeoutaneously, since each product card uses similar style properties. I also made use of the nth-child() property and used it to select a specific product card.

```html
<div class="product-box">
  <img class="product-img" src="./images/icon-sedans.svg" alt="sedan image" />
  <h2 class="product-header">Sedans</h2>
  <p class="product-info">
    Choose a sedan for its affordability and excellent fuel economy. Ideal for
    cruising in the city or on your next road trip.
  </p>
  <button class="product-button sedan-button">Learn More</button>
</div>
```

```css
.product-box:first-child {
  background-color: hsl(31, 77%, 52%);
  border-radius: 10px 0 0 10px;
}

.product-box:nth-child(2) {
  background-color: hsl(184, 100%, 22%);
}

.product-box:nth-child(3) {
  background-color: hsl(179, 100%, 13%);
  border-radius: 0 10px 10px 0;
}
```

### Continued development

I would like to continue developing this project by determining the spacing more accurately, since there are some areas with an unusual amount of spacing.

### Useful resources

- [W3Schools justify-content property](https://www.w3schools.com/cssref/css3_pr_justify-content.php) - This helped me try different parameters for the justify-content property to determine which one would give the best spacing.

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/Grunt395](https://www.frontendmentor.io/profile/Grunt395)
