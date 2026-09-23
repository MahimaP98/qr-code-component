# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Links

- Solution URL: [https://github.com/MahimaP98/qr-code-component]
- Live Site URL: [https://mahimap98.github.io/qr-code-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid (for centering the card on the page)
- Mobile-first / single fixed-width card layout
- Google Fonts (Outfit)

### What I learned

This was my first Frontend Mentor challenge, so the focus was really just getting comfortable with the basics — turning a static design into working HTML and CSS from scratch.

  A couple of things I practiced:
  - Using display: grid with justify-content: center on the body to center a card both horizontally on the page without extra wrapper divs.
  - Keeping the markup semantic and simple — one card container, an image, and a heading/paragraph pair — rather than over-nesting divs.

```css
body {
  display: grid;
  justify-content: center;
  background-color: hsl(212, 45%, 89%);
}
```

### Continued development

Things I want to focus on in upcoming challenges:

  - Responsive design with media queries — this solution currently uses one fixed layout. The challenge comes with separate mobile and desktop designs, so my next step is adding a @media breakpoint and comparing both against the actual designs.
  - CSS custom properties — starting to use :root variables for colors and spacing instead of repeating hsl() values, so the styles are easier to maintain as projects grow.
  - Accurate spacing from design files — getting more comfortable eyeballing padding/margin/font-size from a static JPG design and checking it against the style guide.

### AI Collaboration

I used Claude for support on this project, specifically for:

 - Understanding what files/sections a Frontend Mentor submission actually needs (repo URL, live URL).
 - Getting guidance on how to turn this template into a proper README rather than writing the whole file for me.

I did the HTML/CSS build myself — AI was used for the submission process and documentation, not for generating the solution code.

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/MahimaP98]

