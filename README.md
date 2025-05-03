# Frontend Mentor - Order summary card solution

This is a solution to the [Order Summary Card Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements
- View alternate background images and responsive sizing based on mobile or desktop screens

### Screenshot

![](./images/result-preview.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Using a mobile-first approach, I first re-create the provided mobile design template as accurately as possible with CSS and HTML. This process takes the most time as I make several passes to ensure the result is both accurate to the design's wireframe and also utilizing DRY code. From there, I added the challenge's requested media queries to allow for desktop viewing by modifying background image pathways and sizing.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

A big struggle for me on this project was that it was my first time utilizing CSS Grid in a practical application. While I was familiar with the usual Flexbox horizontal and vertical alignment rules of 'justify-content/self' and 'align-content/self', Grid utilizes 'justify-<b>items</b>' and 'align-<b>items</b>'. That was something new I didn't know before, and I was excited to learn it to help solve this challenge! 

```css
.pricing-table {
    display: grid;
    grid-template-columns: 0.8fr 1.985fr 2fr;
    justify-items: center;
    gap: 0.93em;
}
```

### Continued development

- CSS Grid
- CSS Flexbox
- Mobile-first and Responsive Design

### Useful resources

- [CSS Grid and Align-Items/Justify-Items- Centering Text in CSS Grid](https://stackoverflow.com/questions/45536537/centering-in-css-grid)

## Author

- Website - [Val](https://github.com/valryanb)
- Frontend Mentor - [@valryanb](https://www.frontendmentor.io/profile/valryanb)