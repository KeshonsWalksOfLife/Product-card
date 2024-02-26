# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
-  [My process](#my-process)
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
- See hover and focus states for interactive elements

### Screenshot

![](./Product-card%20.png)
![](./Product-card%20mobile.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

The art of responsive design, It was my first time creating a responsive design that feels fluid and not overbearing, thanks to Daniel Hernandez from 100Devs for the assistance on growing an understanding of @media queries. 

@media (min-width: 890px) {
    .body-container {
        display: flex;
        background: linear-gradient(180deg, 
        var(--primary-color),
        var(--linear-color));
    }

    .container {
        width: 40vw;
        height: 32vw;
        display: flex;
        flex-direction: row;
        margin-top: 160px;
        margin-left: 381px;
    }

  @media (min-width: 890px) {
    .body-container {
        display: flex;
        background: linear-gradient(180deg, 
        var(--primary-color),
        var(--linear-color));
    }

    .container {
        width: 40vw;
        height: 32vw;
        display: flex;
        flex-direction: row;
        margin-top: 160px;
        margin-left: 381px;
    }
.box-shadow {
    width: 72%;
    height: 75vh;
    background: linear-gradient( to top, var(--secondary-color),
    rgba(250,250,250,0.1), rgba(250,250,250,0.2));
    opacity: 0.6;
    margin-top: 100px;
    margin-left: 280px;
    box-shadow: 0 0 24px 2px rgba(0 ,0 ,0, 0.4);
}

    .picture {
        width: 440px;
        height: 100%;
        margin-left: -30px;
        border-radius: 15px 0 0 15px;
    }

    .description {
        font-size: 14px;
        display: inline-block;
        width: 50%;
    }

    h1, h2, h3, h4, p, h6, button {
        position: relative;
        top: 20px;
    }

h2, h6 {
    display: inline-block;
    margin-left: 30px;
}

    button {
        margin-left: 26px;
    }
}

### Continued development

I am enjoying learning new ways to be more effiecent which helped tremendously. I am thankful to have learned better in responsive design. There is more to come!

### Useful resources

- [Example resource 1](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - This was much needed with using 2 different images and adding them on each size of phone size and desktop size
- [Example resource 2](https://developer.mozilla.org/en-US/docs/Web/CSS/@media) - This taught so much about media queries, I feel way more comfortable of responsive design after reading this reference, I am excited to learn more.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@KeepTheWalkShon](https://www.twitter.com/yourusername)

## Acknowledgments

First and foremost, I want to give it up to Daniel Hernandez for giving the run down on responsive design and helping me through this. Thank you to 100Devs and Leon Noel for teaching me more to understand Software Engineering. Im thankful for what i have learned so far and what I will learn going forward.