# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot (Desktop View)
![screenshot-127 0 0 1_5500-2021 11 24-21_17_15](https://user-images.githubusercontent.com/69512496/143293434-f28dc3bc-5a66-4812-8202-60cda37c609d.png)



### Screenshot (Mobile View)
![screenshot-127 0 0 1_5500-2021 11 24-21_17_52](https://user-images.githubusercontent.com/69512496/143293455-5758d2b9-030e-4451-a974-6a4ac3f8a843.png)



### Links

- Solution URL: [Link](https://github.com/hassanidris/testimonials-grid-section)
- Live Site URL: [Link](https://hassanidris.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned

I have learned how to muniplate the layout according to the device view.

```

/* ---------- Media Query ------------- */
@media only screen and (max-width: 992px) {
  .testimonials {
    grid-template-columns: repeat(3, 1fr);
    grid-template-areas: "moderateViolet moderateViolet   darkGrayishBlue" 
                         "white-a        darkBlackishBlue darkBlackishBlue" 
                         "white-b        white-b          white-b";
  }
}
@media only screen and (max-width: 576px) {
  .testimonials {
    grid-template-columns: repeat(1, 1fr);
    grid-template-areas: "moderateViolet" 
                         "darkGrayishBlue" 
                         "white-a" 
                         "darkBlackishBlue" 
                         "white-b";
  }
}

```

## Author

- Github - [hassanidris](https://github.com/hassanidris)
- Frontend Mentor - [@hassanidris](https://www.frontendmentor.io/profile/hassanidris)


