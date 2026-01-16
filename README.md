# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

Viewable at this link:

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This is my second HTML and CSS challenge. I used some of the knowledge i gained from the first challenged but ran into new issues. Like trying to space the three stat sections evenly and get the image to be the right purple color.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./Screenshot-my-solution.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned what a span is and how to style it in CSS. I also learned about how to create a hue of color over an image. I wasn't able to get the exact color I wanted but it is still purple.

```html
<h1>Get <span class="purple-text">insights</span> that help your</h1>
```

```css
.image-container {
  background-color: hsl(271, 100%, 50%);
  width: 100%;
  height: 100%;
  overflow: hidden;
  /* hsl(244, 37%, 16%) */
  /* line-height: 0; */
  /* display: flex; */

  /* isolation: isolate; */
  /* position: relative;
    display: inline-block; */
}

/* .image-container::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: hsl(277, 64%, 61%);
    background-color: rgba(114, 29, 170, 0.836);
    mix-blend-mode: multiply;
    z-index: 1; }*/

.image-women {
  filter: sepia(50%) saturate(200%);
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
  mix-blend-mode: multiply;
  opacity: 0.75;
}
```

### Continued development

I want to continue focusing on how to organize items on a webpage exactly where I want them and
how to display them on many different sizes of screens.

### Useful resources

Internet

## Author

- Frontend Mentor - [@metalfenser](https://www.frontendmentor.io/profile/metalfenser)

## Acknowledgments

None this time
