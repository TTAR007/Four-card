# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/images/final-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/4-cards-responsive-mobile-first-hEg6cO4wer)
- Live Site URL: [Add live site URL here](https://ttar007.github.io/Four-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- I have learnt that It is more creative to use clamp() for increasing font-size based on screen width.

```css
p {
  color: hsl(212, 6%, 44%);
  font-size: clamp(0.9375rem, 0.825rem + 0.48vw, 1.125rem);
}
```

- I learned to use grid to display all 4 cards.
- I used grid-column and grid-row to span "supervisor card" and "calculator card" and align them in the center.

```css
.card__box:nth-of-type(4) {
  grid-row: 1 / 3;
  grid-column: 3;
  align-self: center;
}
```

### Continued development

In future projects, I will focus on using the right html tags and using "em or rem" to increase accessibility.

## Author

- Website - [Add your name here](Not available yet.)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
