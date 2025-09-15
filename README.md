# Frontend Mentor - Result QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

![Design preview for the QR code component solution coding challenge](/preview.jpg)
![Design preview for the Result QR code component solution coding challenge](/SS.jpeg)
![Design preview for the Result QR code component solution coding challenge](/SS2.jpeg)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

**To do this challenge, you need a basic understanding of HTML and CSS.**

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

# Modern CSS Practices

```css
:root {
  --max-width: 1440px;
  --min-width: 375px;

  /* COLOR */

  --clr-primary-hsl-300: 212, 45%, 89%;
  --clr-primary-hsl-500: 216, 15%, 48%;
  --clr-primary-hsl-900: 218, 44%, 22%;
  --clr-primary-300: hsl(var(--clr-primary-hsl-300));
  --clr-primary-500: hsl(var(--clr-primary-hsl-500));
  --clr-primary-900: hsl(var(--clr-primary-hsl-900));

  /* TYPOGRAPHY */
  --font-family-default: "Outfit", sans-serif;
  --fw-regular: 400;
  --fw-bold: 700;

  --fs-default: 15px;
}
```

# Centering Modern

```css
body {
  font-family: var(--font-family-default);
  font-size: var(--fs-default);
  color: var(--clr-slate-300);
  min-height: 100vh;
  display: grid;
  place-items: center;
  background-color: var(--clr-primary-300);
}
```

## Author

- Frontend Mentor - [@L1mus](https://www.frontendmentor.io/profile/L1mus)
- LINKIN - [@alimustadji](https://www.linkedin.com/in/alimustadji/)
