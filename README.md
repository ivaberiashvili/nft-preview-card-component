# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Original Design:
![Original Design](/design/desktop-preview.jpg)

My solution:
![Desktop](/design/screenshot-desktop.png)
![Desktop - Active](/design/screenshot-desktop-active.png)
![Mobile](/design/screenshot-mobile.png)

### Links
- Live Site URL: [Github Pages](https://github.com/ivaberiashvili/nft-preview-card-component.git)

## My process

- First I started to bring in all the necessary elements like images and header and paragraph texts
- then I created the shapes and defined the correct spacing using margin and padding
- and finally I used flexbox to align the components in my desired positions. 
- then, after adding hover functionality, I realized I needed to change hierarchy in my html structure

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- General workflow lesson I learned was to first create basic structure and add functionality (in this case hover) and only then finalize the design.

- I learned the workaround to making object with different opacity of the same div element - instead of using **#HEX** color - using **rgba** code (which has the alpha channel at the end allowing you to control opacity of the color) allowed me to specify the color of the background and without affecting the whole div element.

- I understood **how box-sizing works** after staring at my screen for almost and hour trying to understand why my elements was several pixels off.

- Also, that **sometimes anchor element doesn't respond to margin** and the easies way I solved it was to nullify all margin and padding, created div container around it and add similar margin to that container.


### Continued development

This was basically the same as the [previous](https://github.com/ivaberiashvili/qr-code-component) project, but with more elements and added functionality of hover - which was quite fun once I understood how it works and I'm eager to test it in my [next project](https://github.com/ivaberiashvili/order-summary-component) and see how far I can go with it. 


### Useful resources

- [Mdn Web Docs > CSS > box-sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing) - This was extremely helpful with real time examples.

## Author

- [Iva](https://github.com/ivaberiashvili)