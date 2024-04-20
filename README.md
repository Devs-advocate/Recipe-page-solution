# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

This was the last FEM challenge of the "Getting Started on Frontend Mentor" learning path.
The challenge took longer than expected, more than 10 hours in total. Difficulties were encountered with styling the lists.

### Screenshot

![Desktop](/assets/images/Desktop%20Frontend%20Mentor%20Recipe%20page.png)
![Mobile](/assets/images/Mobile%20Frontend%20Mentor%20Recipe%20page.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I started with the HTML first looking to be as semantic as I could. No `<div>` tags were used, `<section>` was used as there were clearly definable sections of the page. Ordered and unordered lists, as well as tables were prominent in the HTML.
Next I used the style guide to set out my custom properties. From there, I used a top-down/outside-inside approach to style each section.
I was satisfied with the completion on my elements, when they closely matched the measurements and styling of the provided designs.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

There are various ways to style list markers.

Directly accessing them:

```css
.preparation li::marker {
  color: var(--primary-dark-raspberry);
  font-weight: 800;
  font-size: 13px;
  padding-left: 76px;
}
```

Or deleting them an creating your own:

```html
<li>
  <span class="bullet">&#x2022;</span
  ><span class="item"
    ><span class="bold">Total</span>: Approximately 10 minutes</span
  >
</li>
```

```css
.preparation li {
  display: flex;
  align-items: center;
  padding-left: 26px;
}

.preparation .bullet {
  color: var(--primary-dark-raspberry);
  font-size: 21px;
}
```

### Continued development

Lists and tables are common features in web development and how they're styled. I will look to improve this area, as it took quite a long time to work out how to match designs.

### Useful resources

- [Free Code Camp](https://www.freecodecamp.org/news/dot-symbol-bullet-point-in-html-unicode/) - This helped me with the list bullet points in HTML.
- [Stack Overflow](https://stackoverflow.com/questions/5316545/libefore-content-how-to-encode-this-special-character-as-a-bullit-in-a) - This helped me with the list bullet points in CSS.
- [ChatGPT](https://chat.openai.com/)

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Devs-advocate)
