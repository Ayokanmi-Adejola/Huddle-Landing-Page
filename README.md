# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Desktop Design](./design/desktop-design.jpg)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS variables)
- Flexbox
- Mobile-first workflow
- Google Fonts (Poppins & Open Sans)
- Font Awesome icons
- Responsive design principles

### What I learned

This project helped me practice several key frontend development concepts:

1. **Mobile-first responsive design**: Starting with mobile styles and progressively enhancing for larger screens
2. **CSS custom properties**: Using CSS variables for consistent color theming
3. **Flexbox layouts**: Creating flexible layouts that work across different screen sizes
4. **Hover effects and transitions**: Adding smooth interactive elements with CSS transitions

Key code snippets I'm proud of:

```css
/* CSS Custom Properties for consistent theming */
:root {
  --violet: hsl(257, 40%, 49%);
  --soft-magenta: hsl(300, 69%, 71%);
  --white: hsl(0, 0%, 100%);
}

/* Smooth hover transitions */
.register-btn:hover {
  background-color: var(--soft-magenta);
  color: var(--white);
  transform: translateY(-2px);
  box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.3);
}
```

```html
<!-- Semantic HTML structure -->
<main class="main-content">
  <img src="./images/illustration-mockups.svg" alt="Illustration" class="illustration">
  <div class="content">
    <h1 class="title">Build The Community Your Fans Will Love</h1>
    <p class="description">...</p>
    <a href="#" class="register-btn">Register</a>
  </div>
</main>
```

### Continued development

Areas I want to continue focusing on in future projects:

- **CSS Grid**: While this project used Flexbox effectively, I'd like to explore CSS Grid for more complex layouts
- **Accessibility**: Adding more comprehensive ARIA labels and keyboard navigation
- **Performance optimization**: Implementing lazy loading for images and optimizing font loading
- **Advanced animations**: Creating more sophisticated hover effects and page transitions

## Author

- Frontend Mentor - [@Ayokanmi-Adejola](https://www.frontendmentor.io/profile/Ayokanmi-Adejola)