# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![FireShot Capture Frontend Mentor QR code component-127.0.0.1.png](./images/FireShot%20Capture%20001%20-%20Frontend%20Mentor%20-%20QR%20code%20component%20-%20127.0.0.1.png)

### Links

- Solution URL: [github](https://github.com/Emmanuel-Xs/qr-code-component-main)
- Live Site URL: [a netlify app](https://boisterous-youtiao-6fbb76.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I used a div with a class called card as the container for the QR code card. I gave the card a minimum width of 80% of the viewport or 300px.

centered it in the body with grid and styled it according the design

I had problem with the border box of the card and image, it doesn't looks let me use the word synchronized to me.

**I am writing this 5months later because I want to improve on skills.**

This is the code for ensuring that the size of the card doesn't grow to big. It uses the min() function to ensure that it always takes the smallest size possible of the two

```css
.card {
 width: min(80%, 300px);
}
```

### Continued development

I want to improve on skills on web development in general so that i can start building things on my own and especially use my skills to solve problems that will earn me money and fulfillment

### Useful resources

- [kevin powell](https://www.youtube.com/kevinpowell) - I followed kevin's tutorial but not completely, I tried doing it on my own

## Author

- Frontend Mentor - [Emmanuel-Xs](https://www.frontendmentor.io/profile/Emmanuel-Xs)
- Twitter - [@EmmaNwaohiri](https://www.twitter.com/EmmaNwaohiri)
