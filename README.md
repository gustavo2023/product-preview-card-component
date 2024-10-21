# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Live Site Screencapture](./images/live-site-screencapture.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Product Preview Card Component](https://gustavo2023.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- Learned about using `<picture>` element to serve different images based on the viewport size.

```html
<picture>
  <source
    srcset="images/image-product-desktop.jpg"
    media="(min-width: 64rem)"
  />
  <img
    src="images/image-product-mobile.jpg"
    alt="Gabrielle Chanel Perfume Bottle"
  />
</picture>
```

This approach allowed me great flexibility in order to use multiple image resources, which in return allows for responsive images by ensuring that the proper image is displayed based on the screen size.

## Author

- Frontend Mentor - [@gustavo2023](https://www.frontendmentor.io/profile/gustavo2023)
