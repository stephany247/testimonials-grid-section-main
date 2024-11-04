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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/Screenshot%202024-11-04%20at%2016-08-33%20Frontend%20Mentor%20Testimonials%20Grid%20Section.png)
![](./images/Screenshot%202024-11-04%20at%2016-09-28%20Frontend%20Mentor%20Testimonials%20Grid%20Section.png)



### Links

- Solution URL: [Solution URL here](https://github.com/stephany247/testimonials-grid-section-main)
- Live Site URL: [Live site URL here](https://stephany247.github.io/testimonials-grid-section-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

During this project, I learned how to effectively use CSS Grid to create responsive layouts. Specifically, I explored how to define grid areas and how to manipulate the positioning of elements within the grid.


```css
@media (min-width: 60rem) {
  main {
    gap: 1.5rem;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(2, 1fr);
    display: grid;
    justify-content: center;
    align-self: center;
    grid-template-areas:
      "purple purple grey white-two"
      "white-one black black white-two";
    margin: 6rem 2rem;
    max-width: 67rem;
  }

  article {
    margin: 0 auto;
  }
}
```


### Continued development

In future projects, I plan to focus on enhancing my skills in responsive design to ensure optimal user experience across all devices. Additionally, I want to explore CSS preprocessors like SASS or LESS to streamline my styling process. Finally, I intend to practice more with version control systems like Git to improve my workflow and collaboration skills.

### Useful resources

- [Stack Overflow](https://stackoverflow.com/) - I found helpful solutions for CSS issues, like handling hover effects and box shadows, which were crucial for implementing the card design in this project.
- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This site is my go-to for detailed explanations on HTML, CSS, and JavaScript concepts. It's comprehensive and well-structured.
- [W3Schools - Flexbox Tutorial](https://www.w3schools.com/css/css3_flexbox.asp) - This tutorial helped me understand how to use Flexbox for creating flexible layouts.

## Author

- Website - [Onyinye Stephanie Oguocha](https://www.your-site.com)
- Frontend Mentor - [stephany247](https://www.frontendmentor.io/profile/stephany247)
- Twitter - [@stephanyoguocha](https://x.com/stephanyoguocha)


## Acknowledgments

I would like to give a big thanks to the Frontend Mentor community and the resources on Stack Overflow for helping me troubleshoot and improve my project.
