# Frontend Mentor — Blog Preview Card

A solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

- See hover and focus states for all interactive elements
- View an optimal layout depending on their device's screen size
- Experience a **fully responsive design without any media queries**

### Screenshot

![Blog Preview Card Screenshot](./assets/images/screenshot.png)

### Links

- **Solution URL:** [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/your-solution-url)
- **Live Site URL:** [Live Preview](https://blog-preview-card-plum.vercel.app/)

---

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- **Fluid Design** — fully responsive without media queries
- CSS functions: `clamp()`, `min()`, `max()`
- [Google Fonts — Figtree](https://fonts.google.com/specimen/Figtree)
- Mobile-first workflow

---

### What I Learned

This challenge was a great opportunity to practice **fluid responsive design without media queries**. Here are the key takeaways:

#### 1. Fluid Typography with `clamp()`

```css
font-size: clamp(1.25rem, 5vw, 1.5rem);
```

This scales text smoothly between a minimum and maximum size based on the viewport width — no breakpoints needed.

#### 2. Flexible Spacing with `min()` and `max()`

```css
padding: min(1rem, 5vw);
margin-top: max(2rem, 5vh);
```

These functions let layouts adapt naturally across screen sizes without hardcoded breakpoints.

#### 3. Smooth Hover Effects

```css
.card:hover {
  transform: translateY(-9px);
  transition: all 0.5s ease-in-out;
}
```

A subtle lift on hover adds an interactive, polished feel to the card.

#### 4. Maintaining Image Proportions with `aspect-ratio`

Using `aspect-ratio` kept image dimensions consistent across all viewports without needing JavaScript.

#### 5. Understanding CSS Units

Working through this challenge deepened my understanding of when to use `px`, `rem`, `vw`, and `vh` — and how combining them unlocks truly fluid layouts.

---

### Useful Resources

| Resource | Description |
|---|---|
| [MDN — `clamp()`](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp) | Official docs for the `clamp()` function |
| [CSS Tricks — Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) | Comprehensive flexbox reference |
| [Modern Fluid Typography with `clamp()`](https://www.smashingmagazine.com/2022/01/modern-fluid-typography-css-clamp/) | In-depth article on fluid typography techniques |
| [Google Fonts — Figtree](https://fonts.google.com/specimen/Figtree) | The typeface used in this project |

---

## Author

- **Frontend Mentor** — [@elfahl52](https://www.frontendmentor.io/profile/elfahl52)
- **GitHub** — [@elfahl52](https://github.com/elfahl52)

---

## Acknowledgments

Thanks to [Frontend Mentor](https://www.frontendmentor.io) for this challenge. Building a fully responsive component without a single media query was a genuine insight — it pushed me to think in fluid values rather than fixed breakpoints, and gave me a much clearer mental model of modern CSS functions like `clamp()`, `min()`, and `max()`.
