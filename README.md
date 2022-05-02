# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshots

![](./images/screenshots/Screenshot_1.png)
![](./images/screenshots/Screenshot_2.png)

### Links

- Live Site URL: [Live Server](https://stats-preview-card-component-jlah47.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- CSS Media Querys

### What I learned

While working on this project i needed to change the color of an image, so i learned how to do it, i basically learned the "background-blend-mode" property, and how this property mixes colors from a background color and background images, snippet from code below:

```html
<div class="image"></div>
```
```css
.image{
    background: url(/images/image-header-desktop.jpg);
    background-color: var(--Soft_violet);
    background-blend-mode: multiply;
}
```

More about "background-blend-mode" property [HERE](https://developer.mozilla.org/en-US/docs/Web/CSS/background-blend-mode)

### Continued development

I'm not entirely happy with the CSS architecture in my project, so... I'll keep learning in this area.

I think there are better practices for CSS files, and obviously I want to learn them.

### Useful resources

- [MDN](https://developer.mozilla.org/) - This helped me understand some CSS properties.

## Author

- Frontend Mentor - [@jorgeluisah47](https://www.frontendmentor.io/profile/jorgeluisah47)
