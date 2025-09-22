# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Mobile Preview](<screenshot/NFT Preview - mobile.png>)
![Desktop Preview](<screenshot/NFT Preview - desktop.png>)

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

I learned to implement cube css.

To see how you can add code snippets, see below:

```html
<article class="[ flex-column gap-md-2 ] [ bg-blue-900 ] [ card ]">...</article>
```

```css
.flex-column {
  display: flex;
  flex-direction: column;
}

.gap-md-2 {
  gap: var(--spacing-md-2);
}

.bg-blue-900 {
  background-color: hsl(216, 50%, 16%);
}

.card {
  border-radius: 1rem;
  padding: var(--spacing-md-2);
  margin-inline: auto;
  max-width: 20.4375rem;

  box-shadow: 0 10px 15px rgba(0, 0, 0, 0.3), 0 20px 40px rgba(0, 0, 0, 0.4);
  overflow: hidden;
}
```

### Useful resources

- [cube.fyi](https://cube.fyi/) - Cube css reference.

## Author

- GitHub - [AJ-Tan](https://github.com/AJ-Tan)
- Frontend Mentor - [@AJ-Tan](https://www.frontendmentor.io/profile/AJ-Tan)
