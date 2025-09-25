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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./product-preview-card-component.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- SASS variables
- Flexbox layout
- CSS Grid layout
- Desktop-first workflow

### What I learned

In this project I could improve my understanding in CSS Grid layout, Flexbox layout, meta tag in HTML5 to improve SEO, and Art Direction to show responsive images in different breakpoints.

```html
<!-- Meta tag -->
<meta name="description" content="Product preview card" />

<!-- Art direction for responsive images -->
<picture>
  <source
    srcset="images/image-product-mobile.jpg 1x"
    media="(max-width: 35.875em)"
  />
  <img srcset="images/image-product-desktop.jpg 2x" alt="Image product" />
</picture>
```

```css
/* Grid layout */
.content {
  display: grid;
  grid-template-columns: 1fr 280px;
  grid-template-rows: 420px;
}

/* Flexbox layout */
.content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 1.5rem;
}
```

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Responsive_images) - This helped me to show different images for different brekpoints. I really liked this pattern and will use it going forward.
- [Google Search Central](https://developers.google.com/search/docs/crawling-indexing/special-tags) - This is an amazing article which helped me finally understand meta tag in HTML5 to provide additional information about a page to search engines. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [Adair Costa](https://www.frontendmentor.io/profile/Adair-Costa)
