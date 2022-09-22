# Frontend Mentor - Meet landing page solution!


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


### Screenshot

![](./screenshot/screenshot-desktop.png)

### Links

- Live Site URL: [Live Site at github page](https://deguzman7.github.io/meet-landing-page/)
## My process

### Built with

- Semantic HTML5 markup
- Vanilla CSS
- Grid
- Responsive Design

### What I learned

For sure the best thing I learned in this challenge, was CSS property 'order', because using this property I was able to animate the logo on hover using the selector "~" affecting one div that was before the element hovered, in this case was the logo icon that get animated when I hover on the word "meet".
Also learned how to use grid to switch items instead of order property which i knew already

Example: 

".logo-container {
  order: 2;
  transition: ease-out 1s;
}

/* logo hover effect */
.meet-logo,
.meet-icon {
  transition: ease-out 1s;
}

.meet-logo:hover~.meet-icon {
  transform: rotate(720deg);
  filter: blur(1px);
  transition: 1s ease ;
}

.meet-icon:hover {
  transform: rotate(-720deg);
  filter: blur(1px);
  transition: 1s ease ;
}"

### Useful resources

- [W3 Schools - Order](https://www.w3schools.com/cssref/css3_pr_order.asp) - Order Property


## Author
- Github - [deguzman7](https://github.com/deguzman7/)
- Frontend Mentor - [@deguzman7](https://www.frontendmentor.io/profile/deguzman7)
