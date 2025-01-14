# Frontend Mentor - Workit landing page solution

This is a solution to the [Workit landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-landing-page-using-sass-IqFK6I3KOH)
- Live Site URL: [GitHub Pages](https://valeriamontoya.github.io/workit-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Syntatically Awesome Style Sheets](https://sass-lang.com/)
- Mobile-first workflow

### What I learned

Through this project I was able to recap how the `position` and `z-index` properties work. It was a challenge to match the design but I finally did it.   
Here you can see an example of how I positioned the hero image for mobile layout:

```css
.hero {
  /* Other code */
  &__image {
    width: 298px;
    position: absolute;
    left: 52%;
    bottom: -25%;
    transform: translateX(-50%);
    z-index: 2;
  }
}
```

## Author

- Frontend Mentor - [@ValeriaMontoya](https://www.frontendmentor.io/profile/ValeriaMontoya)
- Twitter - [@val_smf](https://twitter.com/val_smf) 