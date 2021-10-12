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
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [https://github.com/gchristofferson/single-price-grid-component](https://github.com/gchristofferson/single-price-grid-component)
- Live Site URL: [https://single-price-grid-component-eight-beta.vercel.app/](https://single-price-grid-component-eight-beta.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM Methodology


### What I learned

This was a fun little project.  Something new I added to this project was the use of the `transform: scale()` property for a hover effect on the call-to-action button (desktop layout).

Here's how I used it in the CSS:
```css
.price-grid__btn:hover,
.price-grid__btn:focus {
  cursor: pointer;
  transform: scale(1.1, 1.1);
}
```

### Continued development

I'd like to learn and use more CSS animations in my future projects.  Nothing crazy, just some nice subtle effects that will make my designs stand out a bit more.  I'm always interested though in knowing how these things affect performance, so I'd like to learn more about that as well.

## Author

- Frontend Mentor - [@gchristofferson](https://www.frontendmentor.io/profile/gchristofferson)
- Twitter - [@GreggChristoff2](https://twitter.com/GreggChristoff2)

