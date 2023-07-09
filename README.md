# Frontend Mentor - Tip calculator app solution

This is a solution to the [Tip calculator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/tip-calculator-app-ugJNGbJUX). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the app depending on their device's screen size
-   See hover states for all interactive elements on the page
-   Calculate the correct tip and total cost of the bill per person

### Screenshot

![](images/Screenshot%202023-07-09%20at%2000.57.10.png)

### Links

-   Solution URL: [Add solution URL here](https://your-solution-url.com)
-   Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Javscript
-   Desktop-first workflow

### What I learned

it is better to call all the document query selector without including any elements

### Useful resources

MDN DOCS: https://developer.mozilla.org/

```js
// PROUD OF THIS FUNCTION
btnReset.addEventListener('click', function () {
    bill.value = '';
    customPercent.value = '';
    people.value = '';
    tipAmountPerPerson.innerText = '$0.00';
    totalPerPerson.innerText = '$0.00';

    //RESETING THR BUTTONS
    btnReset.classList.remove('active');
});
```

## Author

-   Frontend Mentor - [@Oluwatobiiiiii](https://www.frontendmentor.io/profile/Oluwatobiiiiii)
-   Twitter - [@Oluwatobicodes](https://www.twitter.com/Oluwatobicodes)
