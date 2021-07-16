# Frontend Mentor - Easybank landing page solution

This is a solution to the [Easybank landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/easybank-landing-page-WaUhkoDN). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom propertiesx
- CSS Grid
- Mobile-first workflowes

### What I learned

- I learnt how to design a navbar with javascipt and media queries

To see how you can add code snippets, see below:

```css
@media screen and (max-width: 500px) {
  .topnav.responsive {
    position: relative;
  }
  .topnav.responsive a.icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: center;
  }
}
```

```js
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
```

### Continued development

-- I want to learn more about responsive and beautiful navbars.
-- Using frameworks to reduce workload and design better interface.
-- I would like to learn how to design interface according details anbd design (not mising any information)

### Useful resources

- [Example resource 1](www.w3schools.com/howto/howto_js_responsive_navbar_dropdown.html) - This helped me for the navbar cos i ran into confusion

## Author

- Website - [](https://www.your-site.com)
- Frontend Mentor - [@Blazing-Mike](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@Mikeoxygen](https://www.twitter.com/yourusername)
