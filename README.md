# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned how to use Mixins in SCSS. Mixins are great to way to create a group of CSS code that you will resuse through out your code. That way, you don't have to keep rewriting the same code reptitively. Here's how I used the mixins:

                                                @mixin Flex-Column {
                                                  display flex;
                                                  flex-direction; column;
                                                  justify-content: center;
                                                  align-items: center;
                                                }
Now, instead of writing that same black of code everytime I need to use flexbox, I just incorporate it by using @include Flex Column. I am able to go from 5 lines of code to just one liine of code using mixins.



### Continued development

Building more projects using SCSS. And also improving my mobile workflow layout.

### Useful resources

- [Sass](https://sass-lang.com/) - Sass/SCSS documentation
- [Sass Tutorial](https://www.youtube.com/watch?v=_a5j7KoflTs&t=739s) - Great code along video to learn Sass/SCSS


## Author

- Frontend Mentor - [@taepal467](https://www.frontendmentor.io/profile/taepal467)
- DevTo - [@taepal467](https://dev.to/taepal467)




