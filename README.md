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


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![image](https://github.com/user-attachments/assets/08f0ed2a-9e4b-4ad9-965d-c6fc3933ca8b)



### Links

- Solution URL: [solution](https://simgrant.github.io/social_links/)

## My process

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Certainly! Here's a summary of what you've learned from the CSS-related questions you've asked:

---

### **CSS Basics and Advanced Techniques: What I've Learned**

Over the course of working with CSS, I've learned a variety of techniques that help me write clean, efficient, and maintainable stylesheets. Below are the key concepts and practices that I’ve explored:

---

#### **1. Centering Elements**
- **Centering a Card**: To center a card element, I learned how to use Flexbox for both alignment and distributing space inside the container.

```css
.card {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    width: 370px;
    height: 658px;
}
```

#### **2. Working with Links and Lists**
- **Spanning an Entire `<li>` with an `<a>`**: I can make a link (`<a>`) span the entire list item (`<li>`) by setting the link's `width` to `100%` and using Flexbox on the list item for alignment.

```css
.social a {
    display: flex;
    width: 100%;
    justify-content: center;
    align-items: center;
}
```

#### **3. CSS Pseudo-Classes and Hover Effects**
- **Hover Effects**: I’ve learned how to add hover effects to elements like buttons and list items, which makes the user interface interactive. Using the `:hover` pseudo-class allows me to change the appearance of an element when the user interacts with it.

```css
button:hover {
    background-color: #e74c3c;
}
```

#### **4. Troubleshooting Layout Issues**
- **Breaking Changes When Removing `display: flex`**: When I removed `display: flex` from a container , it caused layout issues because the flex properties (like alignment and spacing) were no longer active. Flexbox is especially useful when dealing with dynamic layouts or when elements need to adapt based on content.
  
- **Responsive Design**: Media queries play a huge role in ensuring that my web pages look great on all devices. I use them to adapt layouts, fonts, and other styles based on different screen sizes.




