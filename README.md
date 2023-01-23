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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/Screen%20Shot%202023-01-22%20at%209.37.06%20PM.png)
![](./images/Screen%20Shot%202023-01-22%20at%209.37.14%20PM.png)

### Links

- Solution URL: [Github Repo](https://github.com/NathanMartinez/fm_stats_preview_card_component)
- Live Site URL: [Github Pages Site](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
.card__header {
	position: relative;
}

/* Header image overlay */
.card__header::after {
	content: '';
	position: absolute;
	background-color: var(--accent-soft-violet);
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	opacity: 0.8;
	mix-blend-mode: hard-light;
}

.card__header__image {
	width: 100%;
}
```

### Continued development

- BEM
- CSS
- Semantic HTML
- React
- Svelte
- Vue
- Nextjs

### Useful resources

- [BEM Introduction](https://getbem.com/introduction/) - This was a great article that answered a lot of questions for me regarding BEM CSS.
- [MindBEMding – getting your head ’round BEM syntax](https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/) - This is a really good reference with understanding BEM a bit further.
- [Scaling Down The BEM Methodology For Small Projects](https://www.smashingmagazine.com/2014/07/bem-methodology-for-small-projects/) - I really liked this article because it helps me more understand BEM and why I should try it.

## Author

- Github - [Github](https://www.your-site.com)
- Frontend Mentor - [@NathanMartinez](https://www.frontendmentor.io/profile/NathanMartinez)
