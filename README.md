# Frontend Mentor - Insure landing page solution

This is a solution to the [Insure landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/insure-landing-page-uTU68JV8). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![./images/](screenshot.PNG)

### Links

- Solution URL: [Github](https://github.com/cmb347827/insure-landing-page-master)
- Live Site URL: [Live Github](https://cmb347827.github.io/insure-landing-page-master/)

## My process

### Built with

- Semantic HTML5 markup
- Sass/SCSS
- Bootstrap
- jQuery/Javascript
- Mobile-first workflow


### What I learned

- I could re-use code from my previous project (sunnyside agency) to dropdown a menu. I only had to change some code for the menu positioning:
   position absolute for the dropdown menu css link and add some code to switch between the hamburger and close icons.
- I had to switch the button image for the dropdown menu, between the hamburger icon and the close icon.
  At first I was trying with JQuery addClass/removeClass to hide/show the close icon. But I could not get that to work.
  I found a helpful stackoverflow post that advised to use toggleClass instead.
- I needed to convert the hsl color value to hex, then I could get the filter values (see link below) to use the css filter property to change the svg colors.
- I wasted time with css background property trying to add the patterns ,first by using img elemements but could not get this to work using the position and z-index css properties, so 
  I switched to using the background property where needed.
- I also realized that I needed to use more BEM naming conventions in order to get proper use of Sass.


### Continued development

- Daily tutorials and projects in HTML5, CSS3, Javascript, Bootstrap, Sass/SCSS. For now, in time I will go re-learn React ect.

### Useful resources
[Stackoverflow post toggleClass](https://stackoverflow.com/questions/39149977/how-to-toggle-between-bootstrap-button-classes-onclick)
[Hex color to css filter converter](https://isotropic.co/tool/hex-color-to-css-filter/)
[BEM naming in Sass](https://css-tricks.com/using-sass-control-scope-bem-naming/)

## Author

- Website - [One of my latest codepens](https://codepen.io/cynthiab72/pen/oNybYON)
- Frontend Mentor - [@cmb347827](https://www.frontendmentor.io/profile/cmb347827)

