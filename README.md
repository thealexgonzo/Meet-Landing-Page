# Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR).

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

![](./assets/Screenshot%202022-04-28%20at%2016-46-32%20Meet%20landing%20page.png)

### Links

- [Live Site URL](https://thealexgonzo.github.io/Meet-Landing-Page/)

## My process

### Built with

- Semantic HTML5 markup
- Sass
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I really enjoyed working on this challenge. I decided to focus on using Sass instead of coding directly in CSS. It was great to learn how to install Sass locally which I'm very proud of having done so, including editing the `package.json` scripts so I'd be able to compile Sass locally too. What I struggled with the most in this challenge was working with the background images, making sure the scale and the positions were set correctly and I'm very happy with the results.

I'm very proud of this code:

```html
<h1>Some HTML code I'm proud of</h1>
```

```scss
.image-hero {
  background-image: url("../assets/tablet/image-hero.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 100%;
  // Very proud of this code
  height: 0;
  padding-top: 41%;
}
```

The reason why is because it allowed to make sure that the background images fit perfectly while also scaling as the viewport changed.

### Continued development

I would like to continue applying Sass to most of my projects as I find that it makes writing CSS a lot easier. I would also like to get better at working with background images and I can't wait to start including navigation menus in future projects and to also start working with JavaScript too, to make my designs more functional.

### Useful resources

- [Controlling background-images | CSS Tutorial](https://www.youtube.com/watch?v=3T_Jy1CqH9k) - This video was very helpful to understand how to position multiple background images. =

## Author

Jesus Alejandro González Rodríguez

- Frontend Mentor - [@thealexgonzo](https://www.frontendmentor.io/profile/thealexgonzo)
