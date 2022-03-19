# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![screenshot](images/screenshot.png)

### Links

- Solution URL: [View codes](https://github.com/jesuisbienbien/huddle-landing-page)
- Live Site URL: [View Live Site](https://jesuisbienbien.github.io/huddle-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- FontAwesome Icons

### What I learned

```html
<div class="contact">
  <ul>
    <li>
      <a href="#">
        <i class="fab fa-facebook-f"></i>
      </a>
    </li>
    <li>
      <a href="#">
        <i class="fab fa-twitter"></i>
      </a>
    </li>
    <li>
      <a href="#">
        <i class="fab fa-instagram"></i>
      </a>
    </li>
  </ul>
</div>
```

```css
.contact {
  margin: 3rem auto 1rem;
  ul {
    display: grid;
    grid-template-columns: repeat(3, minmax(20px, 1fr));

    gap: 1rem;
    margin: 0 auto;
    max-width: 145px;
    li {
      list-style: none;
      border: solid 1px white;
      border-radius: 50%;
      padding: 0.5rem;
      text-align: center;

      i {
        color: white;
      }
    }
  }
}
```

### Continued development

- Responsive layout
- Button styling

### Useful resources

- [Box-shadow examples](https://getcssscan.com/css-box-shadow-examples) - This site provided tons of beautiful CSS box-shadow examples.

## Author

- Github - [Nguyen Nguyen](https://github.com/jesuisbienbien)
- Frontend Mentor - [@jesuisbienbien](https://www.frontendmentor.io/profile/jesuisbienbien)

## Acknowledgments
