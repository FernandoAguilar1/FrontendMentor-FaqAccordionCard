# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./images/desktop-Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/FernandoAguilar1/FrontendMentor-FaqAccordionCard)
- Live Site URL: [Add live site URL here](https://fernandoaguilar1.github.io/FrontendMentor-FaqAccordionCard/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- CSS bem methodology

### What I learned

The better of this chllenge was learn to use the HTML5 details tag. it is used to create an interactive widget that the user can open or close.

```html
<details class="main-container__s2__details">
        <summary class="main-container__s2__details__summary">
          How many team members can I invite?
          <img class="main-container__s2__details__icon" src="./images/icon-arrow-down.svg" alt="arrow down">
        </summary>
        <p class="main-container__s2__details__paragraph">
          You can invite up to 2 additional users on the Free plan. There is no limit on
          team members for the Premium plan.
        </p>
      </details>
```

The use of the [open] state for the details tag is amazing 

```css
.main-container__s2__details[open]{
    font-weight: 700;
}
```

I use transforms in css too, just for the arrow icon
```css
.main-container__s2__details[open] .main-container__s2__details__icon{
    transform: rotate(180deg);
    transition: 300ms;
}
```

### Useful resources

- [Details tag](https://www.geeksforgeeks.org/html5-details-tag/#:~:text=HTML5%20%7C%20tag,-View%20Discussion&text=This%20tag%20is%20used%20to,tag%20is%20new%20in%20HTML5.) - This is a guide to the HTML5 details tag.

- [CSS with BEM methodology](https://www.devbridge.com/articles/implementing-clean-css-bem-method/#:~:text=What%20is%20BEM%3F,by%20following%20some%20simple%20rules.) - Info about Creating clean CSS with BEM methodology.


## Author

- Website - [Fernando Aguilar](https://www.ftxsistemas.com)
- Frontend Mentor - [@FernandoAguilar1](https://www.frontendmentor.io/profile/FernandoAguilar1)
- github - [FernandoAguilar1](https://github.com/FernandoAguilar1)

## Acknowledgments

- [CodingTube](https://www.youtube.com/watch?v=wmtdKzbhz-k) - This is an amazing youtube channel where is a complete tutorial to develop this challenge.