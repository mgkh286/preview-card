# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### Screenshot

## desktop design: https://github.com/mgkh286/preview-card/blob/master/design/desktop-design.jpg

## mobile design: https://github.com/mgkh286/preview-card/blob/master/design/mobile-design.jpg

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/stats-preview-card-component-R5A3Gdw8q)
- Live Site URL: (https://mgkh286.github.io/preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="container">
  <div class="card image">
    <div class="empty"></div>
  </div>
  <div class="cardd">
    <h1>Get <span>insights</span> that help your business grow.</h1>
    <p>
      Discover the benefits of data analytics and make better decisions
      regarding revenue, customer experience, and overall efficiency.
    </p>
    <ul>
      <li><span>10k+</span> companies</li>
      <li><span>314</span> templates</li>
      <li><span>12m+</span> queries</li>
    </ul>
  </div>
</div>
```

```css
.proud-of-this-css {
  --very-dark-blue: hsl(233, 47%, 7%); /* main background */
  --dark-desatyrated-blue: hsl(244, 38%, 16%); /* card background */
  --white: hsl(0, 0%, 100%); /* main heading - state  */
  --slightly-transparent-white: hsla(0, 0%, 100%, 0.75); /* main pargraph */
  --slightly-transparent-white: hsla(0, 0%, 100%, 0.6); /* headings */
}
```

### Useful resources

- [Example resource 1](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - This helped me for documentation and using css variables. I really liked this pattern and will use it going forward.
- [Example resource 2](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is an amazing article which helped me finally understand flexbox layout. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Mohamed khalifA](https://www.your-site.com)
- Frontend Mentor - [@mgkh286](https://www.frontendmentor.io/profile/mgkh286)
- Twitter - [@mmd1790](https://twitter.com/mmd1790)

## Acknowledgments

I tried using CSS flexbox to center the card both horizontally and vertically. It only centered horizontally so I needed to add in a top margin. What's the best way of achieving vertical centering?
