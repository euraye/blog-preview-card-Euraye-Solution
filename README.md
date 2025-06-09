# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [Table of contents](#table-of-contents)
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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/image-demo/Desktop%20Ver.png)
![](/image-demo/Mobile%20Ver.png)


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-blog-preview-card-with-styled-components-and-modern-css-Nl0zomIk4N)
- Live Site URL: [Add live site URL here](https://blog-preview-card-euraye-solution.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Figma](https://www.figma.com/) - For design and prototyping

### What I learned

While working on this project, I learned how to use **media queries** to make the layout responsive for different screen sizes. I also practiced using **hover states** to improve interactivity and user experience.

Here are some code samples that highlight what I learned:

```css
/* Media query for mobile responsiveness */

@media (max-width: 400px) {
  .card {
    width: 90vw;
    padding: 16px;
    gap: 16px;
  }
  .Title {
    font-size: 20px;
  }
  .description,
  .date,
  .learning,
  .author .name {
    font-size: 14px;
  }
}


/* Hover effect for interactive elements */
.Title:hover {
  color: var(--color-yellow, #F4D04E);
}
```

### Continued development
In future projects, I want to continue improving my responsive design skills and deepen my understanding of CSS. I plan to explore more advanced layout techniques and best practices to create even more adaptable and visually appealing interfaces.

### Useful resources
- [MDN Web Docs](https://developer.mozilla.org/) - My go-to resource for understanding HTML, CSS, and JavaScript concepts.
- [Figma](https://www.figma.com/) - Used to get precise sizing and design specifications for the project.

## Author

- Website - [euraye - Vercel](https://blog-preview-card-euraye-solution.vercel.app/)
- Frontend Mentor - [@euraye](https://www.frontendmentor.io/profile/euraye)


