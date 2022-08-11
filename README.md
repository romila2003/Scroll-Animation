# Scroll-Animation

This is apart of the 50 projects in 50 days challenge and is the sixth project.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

- To create a scroll animation, where the boxes transition to frame as you scroll down. The challenge involves HTML, CSS and Javascript.

### Screenshot

# Mobile Preview 

![screenshot](https://github.com/romila2003/Scroll-Animation/blob/main/Mobile%20preview.PNG)

# Mobile Preview - active

![screenshot](https://github.com/romila2003/Scroll-Animation/blob/main/Desktop%20preview%20-%20active.PNG)

# Desktop Preview 

![screenshot](https://github.com/romila2003/Scroll-Animation/blob/main/Desktop%20preview.PNG)

# Desktop Preview - active

![screenshot](https://github.com/romila2003/Scroll-Animation/blob/main/Desktop%20preview.PNG)


### Links

 - Source code: [https://github.com/romila2003/Scroll-Animation](https://github.com/romila2003/Scroll-Animation)
 - Live website: [https://scroll-animation-main.netlify.app/](https://scroll-animation-main.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Plain CSS
- Vanilla Javascript
- Flexbox

### What I learned

I learned more about the `window` and `getBoundingClientRect()` property within Javascript and its use.

Javascript - close and open navbar:

```javascript

window.addEventListener("scroll", checkBoxes)

function checkBoxes() {
    const triggerBottom = window.innerHeight / 5 * 4;

    boxes.forEach(box => {
        const boxTop = box.getBoundingClientRect().top;

        if(boxTop < triggerBottom) {
            box.classList.add("show");
        } else {
            box.classList.remove("show");
        }
    }) 
}

```

### Continued development

For future developments, I should implement the features/concepts learned over the last few projects and future projects, into practical projects/challenges such as the frontendmentor.io projects.


## Author

- Twitter - [@romila003](https://www.twitter.com/romila003)
- Frontend Mentor - [@romila2003](https://www.frontendmentor.io/profile/romila2003)
