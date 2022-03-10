# Launch countdown timer

![Design preview for the Launch countdown timer coding challenge](./design/desktop-preview.jpg)

## Overview

## My process

### Built with

 - Flexbox
 - SCSS
 - Javascript
 - Mobile first
 - Semantic HTML5 markup

### Features

- Implement `prefers-reduced-motion` CSS media feature which is used to detect if the user has requested that the system minimize the amount of non-essential motion it uses. Prevent animations in brief.
- Used `backface-visibility` property. This property defines whether or not the back face of an element should be visible when facing the user. So when I rotate my cards, back of them isn't visible to the user so I can create this nice flip animation.
- Added `.sr-only` element to announce countdown time to screen readers. Also used `aria-live="polite"` attribute to expose dynamic content changes in a way that can be announced by assistive technologies after every minute of countdown.
- For interactive elements like socials icons i used `:focus-visible` pseudo class. This selector indicate focus when it is helpful to the user - such as in cases where the user interacts with the page via a keyboard or some other non-pointing device.
- Hats off to Wes Bos, I found his countdown timer tutorial and it was really helpfull to understand how countdown should work. Even tho it was just tip of the iceberg when it comes to JS in this project i think it was very helpful to understand how countdown timer should work. 

### Useful resources
 
- [Video](https://youtu.be/LAaf7-WuJJQ) - Wes Bos countdown timer tutorial and it was really helpfull to understand how countdown should work. Even tho it was just tip of the iceberg when it comes to JS in this project i think it was very helpful to understand basics of countdown timer.
