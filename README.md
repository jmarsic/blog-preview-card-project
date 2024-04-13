# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS)

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

In this section you can see how project looks at the end.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![My finished desktop design preview](./design/my-desktop-preview.png)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/blog-card-project-RxJeiA0DwD)
- Live Site URL: [Live site URL](https://master--jmarsic-blog-card.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- This is my first time using local fonts :crossed_fingers:

First we need to add `@font-face` rules to load web font:

```css
@font-face {
  font-family: "Figtree";
  src: url(./assets/fonts/static/Figtree-SemiBold.ttf);
}
```

After defining within CSS we use them:

```css
body {
  font-family: "Figtree", cursive;
}
```

### Continued development

This was fun project and I will continue research fonts because I think that is big topic. In future I will try using different approach for minimalising and avoiding `FOUT` (flash of unstyled text) and `FOIT` (flash of inivisible text) using different font file types.

### Useful resources

- [Self-hosting web font files](https://medium.com/going-fullstack/self-hosting-web-font-files-6a46bfc36ffd) - Thanks to Rebecca article I figured how to locally use fonts.
- [Making google fonts faster](https://sia.codes/posts/making-google-fonts-faster/) - This is an amazing article which helped me to understand how page is loaded and how to improve performance to shorten that time.

## Author

- Frontend Mentor - [@jmarsic](https://www.frontendmentor.io/profile/jmarsic)
