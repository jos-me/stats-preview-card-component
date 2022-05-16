# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62) challenge on Frontend Mentor.

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

1. To build out [card component](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62) challenge and get it looking as close to the design as possible.

2. Users should be able to:

   - View the optimal layout depending on their device's screen size

### Screenshot

![screenshot of my solution](/screenshot.png)

### Links

- See my [Stats preview card component](https://www.frontendmentor.io/solutions/stats-preview-card-component-using-sassscss-HJs-Qakw9) solution.
- Live site preview: [Stats preview card component](https://jos-me.github.io/stats-preview-card-component/).

## My process

### Built with

- Semantic HTML5 markup
- SCSS preprocessor
- Flexbox layout
- CSS Grid layout
- Responsive Web Design
- Mobile-first Approach

### What I learned

- While working with SASS maps and mixins, I learn to create reusable media query utility.

```scss
// Breakpoints
$breakpoints: (
  mobile: 375px,
  desktop: 1440px,
);

// media queries
@mixin media($device) {
  /// a media query for a given breakpoint.
  $width: map-get(
    $map: $breakpoints,
    $key: $device,
  );

  @media screen and (min-width: $width) {
    @content;
  }
}
```

### Continued development

For the future projects I need to focus and learn more about the following concepts..

- basics of SASS language
- Work more with images

### Useful resources

- Official [SASS Documentation](https://sass-lang.com/).
- VIDEO Tutorial: [Sass Tutorial for Beginners - CSS With Superpowers](https://youtu.be/_a5j7KoflTs).
- Responsive images: [Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images).

## Author

- Frontend Mentor - [@jos-me](https://www.frontendmentor.io/profile/jos-me)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**
