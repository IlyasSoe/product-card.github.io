# Frontend Mentor - QR code component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### Screenshot

![](./Capture.PNG)
![](./screenshot.png)

### Links

- Solution URL: https://github.com/IlyasSoe/product-card.github.io/
- Live Site URL: https://ilyassoe.github.io/product-card.github.io/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- google fonts


### What I learned

```html
<picture>
  <source media="(max-width:750px)" srcset="./images/image-product-mobile.jpg" width="100%" height="241">
  <source media="(min-width:750px)" srcset="./images/image-product-desktop.jpg" width="100%" height="450">
  <img class="defImg" alt="an image of the product" src="./images/image-product-mobile.jpg" width="100%" height="100%">
</picture>
```
```css
button {
    background-color: var(--color2);
    margin: 26px 26px 0 26px;
    border-radius: 5px;
    color: var(--bgc2);
    padding: 20px;
    height: 24px;
    width: 293px;
    border: none;
}
```
### Continued development

I have no idea ....


## Author

my name is: ilyas oufaraji
