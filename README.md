# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./mobileScreenshot.jpeg)
![](./DesktopScreenshot.jpeg)


### Links

- Solution URL: [Github Repo](https://github.com/badkmw/badkmw-product-preview-card)
- Live Site URL: [Github Pages](https://badkmw.github.io/badkmw-product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Vanilla Javascript


### What I learned

Just learned to create my own Javascript function, it could be a plugin, "someday?"


```js
function (theElement, theFirstSrc, theSecondSrc) {
    if (window.innerWidth > 578) {
                theElement.src = theFirstSrc;
            } else {
                theElement.src = theSecondSrc;
            }
}

```



### Continued development

- Mobile first approach
- Javascript, yes javascript! cause I have a question, how does one make sure the images switch 
immediately cause there is some seconds delay when the images switch on different viewports?


### Useful resources

- [Stack Overflow - JS - If window height is less than ___px, do something - What is wrong with this code?](https://stackoverflow.com/questions/31221601/js-if-window-height-is-less-than-px-do-something-what-is-wrong-with-this) - This helped me to find out how to set a conditional window resize using javascript. I really 
 liked this 
 pattern and will use it going 
 forward.
- [Stack Overflow - Detect when a window is resized using JavaScript ?](https://stackoverflow.com/questions/2996431/detect-when-a-window-is-resized-using-javascript) - 
This helped me
 to figure out how to use the 
window resize function using javascript.



## Author

- Frontend Mentor - [@badkmw](https://www.frontendmentor.io/profile/badkmw)
- Twitter - [@bderrickmatthew](https://twitter.com/bderrickmatthew)



## Acknowledgments

My thanks to Stack Overflow.


