# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Desktop aplication](/design/Screenshot-1440.png)

![Mobile aplication](/design/Screenshot-320.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Mainly strengthening knowledge in Flexbox and CSS Grid

```css Grid
  .card--container {
    max-width: 900px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: repeat(4, 100px);
    gap: 10px;
  }

  .grid--card1 {
    grid-row: 2/4;
  }

  .grid--card2 {
    grid-row: 1/3;
  }

  .grid--card3 {
    grid-column: 2;
    grid-row: 3/5;
  }

  .grid--card4 {
    grid-row: 2/4;
  }
```

### Continued development

Constant learning in Responsive Web Design, pure CSS and its Frameworks such as Boostrap
Frontend Roadmap

### Useful resources

- [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me for Flexbox. I really liked this site and will use it going forward.
- [Platzi CSS Grid Layout Course](https://platzi.com/cursos/css-grid-layout/) - This is a very good course, where a can learn to use CSS Grid on advanced techniques.

## Author
Andres Bonilla
- Frontend Mentor - [@abonilla4](https://www.frontendmentor.io/profile/abonilla4)
- Twitter - [@aabonilla](https://www.twitter.com/aabonilla)
