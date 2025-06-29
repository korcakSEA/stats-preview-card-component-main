# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![](./![alt text](image.png))

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I accept that this solution was not endedd up as the way I wanted. I wish I could code the responsiveness better. However in this project my major learning is blending an image with a background color. As the image does not contain any text it is easier to grab the code.

you can see code snippets below:


```css
.wrapper__img{
    position: relative;
    object-fit: cover;
}
.wrapper__img::after{
    content: '';
    position: absolute;
    inset: 0;   
    background-color: var(--Soft-violet);
    opacity: 0.8;
    mix-blend-mode:multiply;
}
```

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)