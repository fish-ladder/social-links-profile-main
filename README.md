# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

/social-links-profile-main/assets/Screenshot-Frontend-Mentor-Social-links-profile.png

### Links

- Solution URL: [https://github.com/fish-ladder/social-links-profile-main]
- Live Site URL: [https://fish-ladder.github.io/social-links-profile-main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Using border box and a CSS reset for margins made spacing the various elements much easier.

I used an nth-child selector to apply margin to the first 4 link elements only:

```css
#links a:nth-child(n + 1):nth-child(-n + 4) {
  margin-bottom: 16px;
}
```

### Continued development

I need to review semantic markdown concepts and figure out how to apply landmark elements on simple component designs like this.

## Author

- Frontend Mentor - [@fish-ladder](https://www.frontendmentor.io/profile/fish-ladder)
