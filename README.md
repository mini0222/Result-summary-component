# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![screenshot of desktop](./Screenshot-desktop.png)
![screenshot of mobile](./Screenshot-mobile.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

for html, I learned how span can be inline with other elements as well as it can be easily styled with css or javascript.

I learned about how flex-direction can adjust the flow direction of elements with column,low.
I also learned how linear-gradient can blend with multiple colors and you can adjust the flow of color with degree. 



```html
<li class="reaction"> <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 20 20"><path stroke="#F55" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M10.833 8.333V2.5l-6.666 9.167h5V17.5l6.666-9.167h-5Z"/></svg> <p>Reaction </p> <span><div class="each-rate">80 </div> /100</span></li>
```
```css

.left-side {
    display: flex;
    flex-direction: column;
    flex: 1;
    background: linear-gradient(180deg,hsl(252, 100%, 67%),hsl(241, 81%, 54%));
    border-radius: 35px;
    padding: 20px;
    color: white;
    text-align: center;
    
}

.right-side { 
    display: flex;
    flex-direction: column;
    flex: 1;
    padding: 30px;
}

```

### Continued development

I would like to make actual tests for each section and calculate the user's average score, make the application more dynamic by building with javascript.





