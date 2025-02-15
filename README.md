# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
    -   [Table of contents](#table-of-contents)
    -   [Overview](#overview)
        -   [The challenge](#the-challenge)
        -   [Screenshot](#screenshot)
            -   [Desktop Design](#desktop-design)
            -   [Mobile Design](#mobile-design)
        -   [Links](#links)
    -   [My process](#my-process)
        -   [Built with](#built-with)
        -   [What I learned](#what-i-learned)
        -   [Useful resources](#useful-resources)
    -   [Author](#author)
    -   [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover and focus states for interactive elements

### Screenshot

#### Desktop Design

<p align="center">
  <img src="./screenshots/desktop view.png" alt="desktop" width="600"  />
</p>

#### Mobile Design

<p align="center">
	<img src="./screenshots/mobile view.png" alt="mobile" height="500" /> 
</p>

### Links

-   Solution URL: [https://github.com/gargujjwal/Frontend-Mentors-Product-preview-card-component-solution](https://github.com/gargujjwal/Frontend-Mentors-Product-preview-card-component-solution)
-   Live Site URL: [https://gargujjwal.github.io/Frontend-Mentors-Product-preview-card-component-solution/](https://gargujjwal.github.io/Frontend-Mentors-Product-preview-card-component-solution/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

I learned about `<picture>` tag and how to use it and put media queries right inside in HTML.
To see how you can add code snippets, see below:

-   I learned how to control size of image using its container tag
    ```css
    img {
    	max-width: 100%;
    }
    container {
    	width: 600px;
    }
    ```
-   I learned about **100vh** problem in mobile devices
    ```css
    body {
    	height: calc(100vh - 0.1px);
    }
    ```

### Useful resources

-   [Picture Tag](https://www.w3schools.com/tags/tag_picture.asp) - This helped me for putting image according to screen
    size, and I am going use it going forward.

## Author

-   Website - [Ujjwal Garg](https://github.com/gargujjwal)
-   Frontend Mentor - [@gargujjwal](https://www.frontendmentor.io/profile/gargujjwal)
-   Instagram - [@gargujjwal](https://www.instagram.com/gargujjwal/)
-   Linkedin - [@ujjwalgarg100Screenshot 2023-06-03 at 10-33-41 Frontend Mentor Product preview card component.png204](https://www.linkedin.com/in/ujjwal-garg-3a5639243/)
-   Twitter -[@UjwalGarg100204](https://twitter.com/UjwalGarg100204)

## Acknowledgments

[tbsankara](https://www.youtube.com/watch?v=BMOH4zSLTnQ&ab_channel=tsbsankara) YouTube video helped me a lot whenever I
ran into problems. He also taught me about the picture tag in HTML
