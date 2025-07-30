# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  <!-- - [Useful resources](#useful-resources) -->
- [Author](#author)
<!-- - [Acknowledgments](#acknowledgments) -->

## Overview

### Screenshot

![](./Frontend-Mentor-Recipe-page-07-30-2025_02_17_PM.png)


### Links

- Solution URL: [Solution](https://your-solution-url.com)
- Live Site URL: [Recipe Page](https://clembrulee.github.io/recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned to exclude selecting last 2 child in the nutrition table using both the :not and :nth-last-child.

```css
.nutrition-table p:not(:nth-last-child(-n + 2)) {
  border-bottom: 1px solid hsl(30, 18%, 87%);
}
```

### Continued development

Continue to learn other CSS techniques for selecting specific elements.

<!-- ### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.** -->

## Author

- Website - [Clement Sung](https://github.com/clembrulee)
- Frontend Mentor - [@clembrulee](https://www.frontendmentor.io/profile/clembrulee)# recipe-page
