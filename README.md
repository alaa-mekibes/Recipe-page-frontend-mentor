# Frontend Mentor - Recipe page

This is a solution to the [NRecipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./Screenshot.png)

### Links

- Live Site URL: https://alaa-mekibes.github.io/Recipe-page-challenge4

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I have now mastered the use of ordered, unordered and tables. I learned how to:
- keep indent for second line in ordered lists via CSS, by using

```css
li {
    text-indent: calc(-1em - 15px);
    padding-left: calc(1.5em + 15px);
    display: list-item /*Ensure it keep the list-item behavior*/
}
li::before {
content:'';
padding-left: 15px
}
```

- Add border-bottom to table row `<tr>`, in this status we have to add the border-bottom to table column `<td>`.

```css
td {
    text-transform: capitalize;
    border-bottom: 1px solid var(--Stone-150);
    padding-bottom: 15px;
    padding-left: 30px 
}
```

- We can't add a padding between rows, but in the selector `table` we can add this :
```css
table {
border-spacing: 0px 15px /* horizontal <length> | vertical <length> */
}
```
