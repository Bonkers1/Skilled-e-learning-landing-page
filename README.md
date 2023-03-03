# Frontend Mentor - Product preview card component solution

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

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./Screenshot%20from%202023-03-02%2023-12-07.png)



### Links

- Solution URL: [product-review-card-component-205ewcajr-bonkers1.vercel.app](https://your-solution-url.com)
- Live Site URL: [product-review-card-component-205ewcajr-bonkers1.vercel.app](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned to finally make a mobile version of this layout and am proud that I was able to make it :D.

To see how you can add code snippets, see below:

```css
@media (max-width: 375px) {
  * {
    margin: auto;
    padding: auto;
  }

  h2 {
    font-family: "Fraunces", serif;
    font-size: 24px;
    align-items: center;
    justify-content: center;
    text-align: left;
    margin: 20px 20px 10px 10px;
    padding: 0 0 0 20px;
  }

  h4 {
    color: var(--dark-grayish-blue);
    font-size: 14px;
    letter-spacing: 2px;
    text-align: left;
    margin-left: 20px;
    margin-top: 20px;
    margin-bottom: 20px;
  }

  p {
    font-size: 12px;
    color: var(--dark-grayish-blue);
    line-height: 1.5rem;
    align-items: center;
    justify-content: center;
    text-align: left;
    margin: 10px 20px 20px 10px;
    padding: 0 0 0 20px;
  }

  #img {
    display: none;
  }

  #img2 {
    display: flex;
    border-top-left-radius: 5%;
    border-top-right-radius: 5%;
    margin: 30px 20px 0 20px;
    width: 300px;
  }

  #cart {
    margin: 0 20px 0 0;
  }

  .btn {
    background-color: var(--dark-cyan);
    border: none;
    border-radius: 10px;
    color: var(--white);
    cursor: pointer;
    font-family: "Montserrat", sans-serif;
    -webkit-border-radius: 10px;
    -moz-border-radius: 10px;
    -ms-border-radius: 10px;
    -o-border-radius: 10px;
    display: flex;
    flex-direction: row;
    text-align: center;
    align-items: center;
    justify-content: center;
    margin: auto;
  }

  .card {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .container {
    background-color: var(--white);
    border-top-right-radius: 0;
    border-bottom-left-radius: 5%;
    border-bottom-right-radius: 5%;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 0 20px;
  }
} ;
```

### Continued development

I want to focus on improving the fundamentals of HTML CSS and Javascript before moving on to a framework.

### Useful resources

- [Google](https://www.example.com) - This helped me get better at looking up solutions and examples. Sometimes I couldn't figure out things so Google helped. Honestly the amount of times people saying "Google is your friend" is not wrong.

- [Stack Overflow](https://stackoverflow.com/) - Same as with Google usually when I was looking for something related stack overflow would pop up on my feed most of the time.

## Author

- Frontend Mentor - [@Bonkers1](https://www.frontendmentor.io/profile/Bonkers1)
