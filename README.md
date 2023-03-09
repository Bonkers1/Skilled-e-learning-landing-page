# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./Screenshot%20from%202023-03-08%2016-39-55.png)

### Links

- Solution URL: []()
- Live Site URL: []()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Placing limits and breakpoints between each screen size was very confusing at first but did let me reinforced what I learned and use media query more often now.

```
@media screen and (min-width: 481px) and (max-width: 768px) {
  main {
    position: relative;
    overflow-x: hidden;
  }

  h1 {
    color: var(--dark-blue);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: left;
    font-family: "Plus Jajarta Sans", sans-serif;
    font-size: 2.5rem;
    margin: 0 0 0.5em 0.3em;
    padding: 0 5em 0 0;
  }

  h2 {
    color: var(--light-gray);
    font-size: 1rem;
    text-align: center;
    line-height: 1.5;
    text-align: left;
    margin: 0 0 0.5em 0;
    padding: 0 8em 0 1em;
  }

  h3 {
    color: var(--white);
    font-family: "Plus Jajarta Sans", sans-serif;
    font-size: 1.5rem;
    align-items: center;
    justify-content: center;
    text-align: center;
    line-height: 1;
    text-align: left;
    margin: 3em 10em 1.5em 1em;
    width: 70%;
  }

  h4 {
    font-family: "Plus Jajarta Sans", sans-serif;
    color: var(--dark-blue);
    text-align: left;
    margin: 1em 0 1em 1em;
  }

  h5 {
    color: var(--light-gray);
    font-size: 1rem;
    text-align: left;
    margin: 0 1em 0 1em;
  }

  h6 {
    color: var(--dark-pink);
    font-size: 1rem;
    text-align: left;
    margin: 1em 0 1em 1em;
  }

  body {
    font-family: "Plus Jajarta Sans", sans-serif;
  }

  nav {
    background-image: url("../assets/image-hero-tablet@2x.png");
    background-position: 25em -5em;
    background-repeat: no-repeat;
    background-size: 40em;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    height: 35em;
  }

  footer {
    background-color: var(--dark-blue);
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    height: 7em;
    width: 100%;
  }

  .btn {
    background-color: var(--dark-blue);
    border-radius: 2rem;
    -webkit-border-radius: 2rem;
    -moz-border-radius: 2rem;
    -ms-border-radius: 2rem;
    -o-border-radius: 2rem;
    border: none;
    color: var(--white);
    cursor: pointer;
    align-items: center;
    text-align: center;
    justify-content: center;
    margin: 2em 4em 1em 0;
    width: 7rem;
    height: 2rem;
  }

  .btn:active {
    background-color: var(--light-gray);
  }

  .btn-1 {
    background: linear-gradient(rgb(72, 81, 255), rgb(240, 42, 166));
    border-radius: 2rem;
    -webkit-border-radius: 2rem;
    -moz-border-radius: 2rem;
    -ms-border-radius: 2rem;
    -o-border-radius: 2rem;
    border: none;
    color: var(--white);
    cursor: pointer;
    align-items: center;
    text-align: center;
    justify-content: center;
    margin: 0 4em 0 0;
    width: 7rem;
    height: 2rem;
  }

  .btn-1:active {
    background-color: var(--light-gray);
  }

  .btn-2 {
    background: linear-gradient(rgb(240, 42, 166), rgb(255, 111, 72));
    border-radius: 2rem;
    -webkit-border-radius: 2rem;
    -moz-border-radius: 2rem;
    -ms-border-radius: 2rem;
    -o-border-radius: 2rem;
    border: none;
    color: var(--white);
    align-items: center;
    text-align: center;
    justify-content: center;
    margin: 1em 30em 0 1em;
    width: 9rem;
    height: 3rem;
  }

  .btn-3:active {
    background-color: var(--light-gray);
  }

  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin: 0 30em 50em 1em;
  }

  .container-1 {
    background: linear-gradient(rgb(255, 111, 72), rgb(240, 42, 166));
    border-radius: 5%;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 0 1em 0 1em;
    width: 21em;
    height: 17em;
    -webkit-border-radius: 5%;
    -moz-border-radius: 5%;
    -ms-border-radius: 5%;
    -o-border-radius: 5%;
  }

  .img {
    margin: 2em 0 3em 2em;
  }
  .img-2 {
    align-items: center;
    margin: 1em 20em 0 1em;
  }
  .img-3 {
    justify-content: space-around;
    margin: 0 0 0 2em;
  }

  .hero {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 0 0 0 0;
  }

  .main-container {
    background-color: var(--white);
    box-shadow: 12px 12px 2px 1px rgba(0, 0, 255, 0.1);
    border-radius: 5%;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 1em 0 1em 1em;
    width: 21em;
    height: 17em;
    -webkit-border-radius: 5%;
    -moz-border-radius: 5%;
    -ms-border-radius: 5%;
    -o-border-radius: 5%;
  }
  .main-container2 {
    background-color: var(--white);
    box-shadow: 12px 12px 2px 1px rgba(0, 0, 255, 0.1);
    border-radius: 5%;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 0 0 1em 1em;
    width: 21em;
    height: 19em;
    -webkit-border-radius: 5%;
    -moz-border-radius: 5%;
    -ms-border-radius: 5%;
    -o-border-radius: 5%;
  }
  .main-container3 {
    background-color: var(--white);
    box-shadow: 12px 12px 2px 1px rgba(0, 0, 255, 0.1);
    border-radius: 5%;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 0 0 1em 1em;
    width: 21em;
    height: 19em;
    -webkit-border-radius: 5%;
    -moz-border-radius: 5%;
    -ms-border-radius: 5%;
    -o-border-radius: 5%;
  }
  .main-container4 {
    background-color: var(--white);
    box-shadow: 12px 12px 2px 1px rgba(0, 0, 255, 0.1);
    border-radius: 5%;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 0 0 5em 1em;
    width: 21em;
    height: 19em;
    -webkit-border-radius: 5%;
    -moz-border-radius: 5%;
    -ms-border-radius: 5%;
    -o-border-radius: 5%;
  }
  .main-container5 {
    background-color: var(--white);
    box-shadow: 12px 12px 2px 1px rgba(0, 0, 255, 0.1);
    border-radius: 5%;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 0 0 5em 1em;
    width: 21em;
    height: 19em;
    -webkit-border-radius: 5%;
    -moz-border-radius: 5%;
    -ms-border-radius: 5%;
    -o-border-radius: 5%;
  }

  .paragraph {
    text-align: center;
    margin: auto;
  }
}

```

### Continued development

Flex and Grid are both very useful tools and we're very interesting when using them for this project.
End up using Flexbox but will definitely be reusing these for future projects to improve and master them.

### Useful resources

- [FreeCodeCamp](https://www.freecodecamp.org/news/css-media-queries-breakpoints-media-types-standard-resolutions-and-more/) - Helped realize that doing mobile first then desktop was the best approach. You learn something new everyday.

## Author

- Frontend Mentor - [@Bonkers1](https://www.frontendmentor.io/profile/Bonkers1)

# Skill-e-learning-landing-page

# Skilled-e-learning-landing-page
