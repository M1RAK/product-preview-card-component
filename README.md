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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/M1RAK/product-preview-card-component)
- Live Site URL: [Add live site URL here](https://product-card-component-preview.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Using this little snippet from Kevin Powell saved me from writing js code or using background-image attribute styles.
```html
<picture>
  <source srcset="./images/image-product-desktop.jpg" 
      media="(min-width:600px)">
      <img src="./images/image-product-mobile.jpg"
      alt="image-product-mobile" 
      class="main-hero-img">
     </picture>
</picture>
```


### Continued development
Build More seemingly simple, pull you into an abyss of your own ignorance Projects.

### Useful resources
- [Kevin Powell](https://youtu.be/B2WL6KkqhLQ) - This is an amazing video which helped me with switching the images using the Picture attribute. 

## Author

- Website - [Abdullahi Ismail](https://www.ara-portfolio.vercel.app)
- Frontend Mentor - [@M1RAK](https://www.frontendmentor.io/profile/M1RAK)
- Twitter - [@MEHRAHKII](https://www.twitter.com/@MEHRAHKII)

## Acknowledgments

Kevin Powell's Solution on using the Picture attribute was immensely helpful,
checkout his solution on youtube.
