# Frontend Mentor - Advice generator app solution

This is a solution to the [Advice generator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/advice-generator-app-QdUG-13db). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Links

- Solution URL: [Advice generator app solution](https://www.frontendmentor.io/solutions/advice-generator-app-solution-CjjKdb_yq)
- Live Site URL: [Live](https://luciana-santos.github.io/advice-generator-app-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Sass
- Mobile-first workflow

### What I learned
```js
fetch('https://api.adviceslip.com/advice')
  .then(r => r.json())
  .then(advice => {
    advId.innerText = advice.slip.id
    quote.innerText = advice.slip.advice
  })
```

## Author

- Frontend Mentor - [@Luciana-Santos](https://www.frontendmentor.io/profile/Luciana-Santos)
- Linktree - [@Lucianadss](https://linktr.ee/Lucianadss)

