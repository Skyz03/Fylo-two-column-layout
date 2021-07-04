# Frontend Mentor - Fylo landing page with two column layout solution

This is a solution to the [Fylo landing page with two column layout challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
This FYLO tow column layout is a pretty cool layout where different CSS avialable features such as CSS Grid & CSS Flexbox is used to make the layout. This site is pretty flexible where both Flexbox and Grid can be used in different ways to implement the same section and vice versa.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![image](https://user-images.githubusercontent.com/42742924/124389485-0991ed00-dd07-11eb-9de1-f06f724a95a2.png)
![Screenshot 2021-07-04 at 20-31-21 Fylo landing page with two column layout](https://user-images.githubusercontent.com/42742924/124389552-61305880-dd07-11eb-99b7-0d278f23bdad.png)


### Links

- Solution URL: https://github.com/Skyz03/Fylo-two-column-layout
- Live Site URL: https://skyz03.github.io/Fylo-two-column-layout/

## My process
I implemented a simple process of following the design by creating the navigation using flexbox, Hero-section, Teams  & CTA section via Flexbox and finally footer via CSS Grid system and made it responsive as follows using these same system.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Animate JS

### What I learned

There are many things I learned in this process first is got a good grips of ```CSS Flexbox and Grid``` system to make the layout of the site. and Secondly the use of ```Animate JS``` to animate while scrolling in the page. Also i Leanred a basic about the ```::befor & ::after``` elements.

To see how you can add code snippets, see below:

```css

  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />

.testomonial::before {
  content: "";
  background: url(images/icon-quotes.svg) no-repeat;
  height: 100%;
  width: 100%;
  position: absolute;
}


@keyframes color {
  0% {
    background-color: red;
  }

  50% {
    background-color: blue;
  }

  100% {
    background-color: greem;
  }
}
```
```js
 <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
  
  data-aos="fade-left"
}
```

### Continued development
Implementation of form valiadation and future custom addition can be added in this project.

### Useful resources

- Animate JS
- CSS FlexBox & Grid MDN Docs

## Author

- Website - Skyz03
