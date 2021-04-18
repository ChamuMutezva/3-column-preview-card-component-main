# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements
- use assistive technologies
### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [solution URL](https://github.com/ChamuMutezva/3-column-preview-card-component-main)
- Live Site URL: [live site](https://chamumutezva.github.io/3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Sass (and sass modules)
- Flexbox
- Mobile-first workflow
- [Parceljs](https://parceljs.org/) - sass processor

### What I learned

- Invisible Content Just for Screen Reader Users. Content to be read by a screen reader but
 not to be seen on the screen. Put the class below on an element that should not be visually
 present.
 - method 1
 ```
  .sr-only {
    position:absolute;
    left:-10000px;
    top:auto;
    width:1px;
    height:1px;
    overflow:hidden;
  }
```

Source [CSS in Action](https://webaim.org/techniques/css/invisiblecontent/) to learn more.

- parceljs error/bug during build
**html head section**
    use this during production. the project failed  to run during `npm run build`.  comment the line below in the head section to solve the issue and return the line when done with build
     `<link rel="stylesheet" href="./css/style.css" />`
    use this for development. the project failed to run during `npm run build`. 
    comment the .scss line below in the head section to solve the issue and return the line when done with build.  `<link rel="stylesheet" href="./scss/style.scss" />`

    ** COMMENT OUT THE LINK STYLES TO SOLVE ISSUE **

    ```
    ×  C:\Users\Precious Mutezva\OneDrive\Documents\Github\3-column-preview-card-component-main\css\style.css:undefined:undefined: plugin is not a function
    at LazyResult.run (C:\Users\Precious Mutezva\OneDrive\Documents\Github\3-column-preview-card-component-main\node_modules\parcel-bundler\node_modules\postcss\lib\lazy-result.js:288:14)
    at LazyResult.asyncTick (C:\Users\Precious Mutezva\OneDrive\Documents\Github\3-column-preview-card-component-main\node_modules\parcel-bundler\node_modules\postcss\lib\lazy-result.js:212:26)
    at C:\Users\Precious Mutezva\OneDrive\Documents\Github\3-column-preview-card-component-main\node_modules\parcel-bundler\node_modules\postcss\lib\lazy-result.js:254:14
    at new Promise (<anonymous>)
    at LazyResult.async (C:\Users\Precious Mutezva\OneDrive\Documents\Github\3-column-preview-card-component-main\node_modules\parcel-bundler\node_modules\postcss\lib\lazy-result.js:250:23)
    at LazyResult.then (C:\Users\Precious Mutezva\OneDrive\Documents\Github\3-column-preview-card-component-main\node_modules\parcel-bundler\node_modules\postcss\lib\lazy-result.js:131:17) ```

### Continued development
- improve on accessibility


### Useful resources
- [CSS in Action](https://webaim.org/techniques/css/invisiblecontent/) , Hiding elements that should be read by screenreaders only.

## Author

- Website - [Chamu Mutezva](https://github.com/ChamuMutezva)
- Frontend Mentor - [@ChamuMutezva](https://www.frontendmentor.io/profile/ChamuMutezva)
- Twitter - [@ChamuMutezva](https://twitter.com/ChamuMutezva)


## Acknowledgments

Frontend Mentor - for the challenge
