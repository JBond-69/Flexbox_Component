# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: #NoneForNow
- Live Site URL: #NoneForNow

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

The most interesting part was creating the layout of the flexbox using the break element, which is basically an empty row in the flexbox
with the single purpose of deciding the layout of the flexbox and separating the elements inside the flexbox. It is a very simple method
that can be used effectively to decide the layout of the flexbox.

To see how you can add code snippets, see below:

```html
<div class="break"></div>
```
```css
.break{
	flex-basis: 100%;
	height: 0;
	padding: 1%;
	background-color: white;
}
```

### Continued development

More complex challenges in static webpages await. This was a very simple static page which I developed with the aim of learning and understanding 
fundamental concepts of flexbox and it's commmonly used attributes as well as layouts.


## Author

- Name - Prannoy Tugiti
- Frontend Mentor - [@JBond-69](https://www.frontendmentor.io/profile/JBond-69)


## Acknowledgments

W3Schools -  For it's expceptional online IDE and the simple explanations for the core concepts of flexbox and it's attributes.
