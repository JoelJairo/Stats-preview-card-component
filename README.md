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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/stat-card-component/](https://www.frontendmentor.io/solutions/stat-card-component-using-html-responsive-pictures-and-css-blend-mode-3wTymlcmw)
- Live Site URL: [https://joeljairo.github.io/stats-preview-card-component/](https://joeljairo.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

```html
<!-- Responsive Pictures with HTML -->
<picture>
  <source
    media="(min-width: 1146px)"
    srcset="images/image-header-desktop.jpg"
  />
  <img
    src="images/image-header-mobile.jpg"
    alt="People in a friendly work environment"
  />
</picture>
```

```css
/* Blend Mode in CSS */
.image-background {
  background-color: var(--soft-violet);
  border-radius: var(--image-border-radious);
}
... img {
  max-width: var(--card-max-width);
  width: 100%;
  mix-blend-mode: multiply;
  opacity: 80%;
  border-radius: var(--image-border-radious);
}
```

### Useful resources

- [https://www.linkedin.com/learning/html-essential-training-4/responsive-pictures](https://www.linkedin.com/learning/html-essential-training-4/responsive-pictures?contextUrn=urn%3Ali%3AlyndaLearningPath%3A5ebaefdc498e440b07b53ea1) - This helped me understanding the responsive pictures in HTML.
- [https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) - Here I learned how to set the image overlay mode based on the background color of the element behind.

## Author

- Frontend Mentor - [@JoelJairo](https://www.frontendmentor.io/profile/JoelJairo)
