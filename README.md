# Frontend Mentor - Insure landing page solution

This is a solution to the [Insure landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/insure-landing-page-uTU68JV8). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: (https://ffinsure-landing-page.netlify.app/)

## My process

- Used Symantic HTML5 markup to create the structure of the page.
- Used CSS custom properties to style the page.
- Used Flexbox and CSS Grid to position the elements in the page.
- Used Media Queries to make the page responsive to different screen size.
- Added hover states to the interactive elements on the page.
- Added a bit of Javascript to provide the toggle functionality in mobile view.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

- Learned how to use override propery to hide the overlapping pattern in the background.
- Positioning a pattern on the left hand side and right hand side using CSS properties only.
- How to use media queries to make the page responsive to different screen size.
- How to position the image to give it a hanging look.

### Challenges I faced

- Positioning the pattern on the left hand side and right hand side using CSS properties only.
- And adjusting this pattern on the smaller screen size because the pattern gets overlapped in bigger screen. Hence I could not position the pattern properly in smaller screen.

### Accessibility feedback i got

--Comment-1: The page content should be contained by landmarks

`<section class="section" id="different">`

-🧩 Common mistakes to avoid

❌ No <main> tag at all.

❌ More than one <main> tag. (You can have multiple <section>s, but only one <main>.)

❌ Nesting <main> inside another landmark (like inside <header> or <footer>).

To fix:

Add exactly one <main> in your HTML.

Wrap all main page content inside it.

Make sure it’s not inside <header>, <nav>, or <footer>.

--Comment-2: Heading levels should only increase by one

`<h4 class="service-title">Snappy Process</h4>.`

Headings in HTML represent the outline or hierarchy of your page content.
They help:

Screen readers understand document structure.

Search engines understand topic organization.

Users visually follow the flow of information.

The rule says:
➡️ You should not skip heading levels.

So you shouldn’t go from an <h1> directly to an <h4> — you should go <h1> → <h2> → <h3> → <h4> in order.
So changed the heading in services section from <h3> to <h4>.

### Continued development

- I want to work on improving the responsive design and adding more animations to the page.

### Useful resources

- [MSDN Website](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_box_model/Introduction_to_the_CSS_box_model) - This helped me to quickly understand different aspects of css.
- [W3 Schools](https://www.w3schools.com/css/css_boxmodel.asp) - This helped me to quickly understand different aspects of css.
- [CSS Tricks](https://css-tricks.com/box-sizing/) - This helped me to quickly understand different aspects of css.

## Author

- Website - [@Suparnaen](https://www.frontendmentor.io/profile/Suparnaen)
- Frontend Mentor - [@Suparnaen](https://www.frontendmentor.io/profile/Suparnaen)
