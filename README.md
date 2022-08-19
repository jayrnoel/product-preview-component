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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- BEM

### What I learned

In this project, I learned how to use `object-fit` to contain my image the card.

```css
.card__img {
  width: 50%;
  height: 460px;
  object-fit: cover;
}
```

It is supposed to be on the `img` with the width and height declared.
`object-fit` will allow your image element to act like a background-image where you can change how the image would react to re-sizing. `cover` will use the full width of the parent element and clip out the excess. `contain` will resize your image without affecting the aspect ratio of the image so the whole image would fit into the whole parent element.

I also started using BEM as a naming system for my classes. I really made a difference when thinking of the context of the class is. It also made selection of css less clunky instead of using descendants.

**BEM**

### Useful resources

- [How to use object-fit](https://www.youtube.com/watch?v=6yAAV-uP0po) - This helped me figure out how to properly use `object-fit`

## Author

- Frontend Mentor - [@jayrnoel](https://www.frontendmentor.io/profile/jayrnoel)
