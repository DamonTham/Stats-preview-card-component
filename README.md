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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/Screenshot.jpg)

### Links

- Solution URL: [https://github.com/DamonTham/Stats-preview-card-component](https://github.com/DamonTham/Stats-preview-card-component)
- Live Site URL: [https://damontham.github.io/Stats-preview-card-component/](https://damontham.github.io/Stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="data">
  <div class="company">
    <h2 class="number">10k+</h2>
    <p class="data-text">companies</p>
  </div>
  <div class="template">
    <h2 class="number">314</h2>
    <p class="data-text">templates</p>
  </div>
  <div class="query">
    <h2 class="number">12M+</h2>
    <p class="data-text">queries</p>
  </div>
</div>
```

```css
.right-panel {
  position: relative;
}

.right-panel::after {
  position: absolute;
  content: "";
  height: 100%;
  width: 100%;
  top: 0;
  left: 0;
  background-color: hsl(277, 64%, 61%);
  opacity: 0.5;
}

.right-panel img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```

<!-- ```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
``` -->

## Author

- Frontend Mentor - [@DamonTham](https://www.frontendmentor.io/profile/DamonTham)
