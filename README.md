# Fylo dark theme landing page - Frontend Mentor

Hi there! Thanks for checking out this project! 👋

This is a solution for a **Frontend Mentor challenge** that consists on building a **landing page** that looks as close to the given design as possible. The goal is to improve my web layout skills by building a realistic project.

## 1. Table of contents ✒️

- [Fylo dark theme landing page - Frontend Mentor](#fylo-dark-theme-landing-page---frontend-mentor)
  - [1. Table of contents ✒️](#1-table-of-contents-️)
  - [2. Overview 🎯](#2-overview-)
    - [The challenge](#the-challenge)
    - [How to run the project:](#how-to-run-the-project)
    - [Links](#links)
  - [3. My process 🧩](#3-my-process-)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [4. Author 🙋🏻](#4-author-)

## 2. Overview 🎯

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

![Design preview for the Fylo dark theme landing page challenge](./src/images/desktop-preview.jpg)

You can checkout the challenge details in the [Frontend Mentor page](https://www.frontendmentor.io/challenges/fylo-dark-theme-landing-page-5ca5f2d21e82137ec91a50fd).

### How to run the project:

I chose to use the Adalab Starter Kit to work on this project, created using Node and Gulp. So first of all it is neccesary to have **[Node JS](https://nodejs.org/)** installed in order to run it.

1. **Open the terminal** in the root folder of the repo.
2. **Install the local dependencies** using the following command in the terminal:

```bash
npm install
```

1. **Start running the project** using the following command that will open a browser window that shows a live version of the page.

```bash
npm start
```

### Links

- Live Site URL: https://leireomadina.github.io/fylo-dark-theme-landing-page/
- Solution URL: coming soon

## 3. My process 🧩

### Built with

- Semantic **HTML5** markup
- HTML **templating system**
- **CSS3** custom properties
- **Flexbox**
- **CSS Grid**
- **SASS** with **BEM** methodology
- **Gulp**
- **Responsive design** with **mobile-first** workflow

### What I learned

- Use **@for** to create **loops in SCSS**: in this case I wanted to select only the second and third card of the testimonial section.

```scss
.card {
  @for $i from 2 through 3 {
    &-#{$i} {
      margin-top: 1.8rem;
      @media all and (min-width: 768px) {
        margin-top: 0;
      }
    }
  }
}
```

- Use and manage **svg files**: use the viewBox attribute to modify its position and dimension, add title and desc tag to improve accessibility, inline and CSS styling, customize colors using fill or stroke...
- Use **ARIA roles** to improve **web accessibilty**: for example, take a look at these navigation menu roles.

```html
<nav class="header-menu" role="navigation">
  <ul class="header-menu__list" role="list">
    <li class="header-menu__list-item" role="list-item">
      <a class="header-menu__link" href="#" role="link">
        Features
      <a>
    </li>
    ...
  </ul>
</nav>
```

### Useful resources

- How to use @for to Create a Sass Loop: https://www.youtube.com/watch?v=6CbsNFXMYgs. You can also take a look at the [official SASS documentation](https://sass-lang.com/documentation/at-rules/control/for).
- List of ARIA roles, states and properties (MDN): https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles
- Inline SVG styling: https://www.youtube.com/watch?v=af4ZQJ14yu8&t=844s
- More resources coming soon..

## 4. Author 🙋🏻

- LinkedIn: [leire-ordeñana-madina](https://www.linkedin.com/in/leire-orde%C3%B1ana-madina/)
- Twitter: [@risingdana](https://twitter.com/risingdana)
- Email: leireomadina@gmail.com
- Behance: [leireomadina](https://www.behance.net/leireomadina)
- Codepen: [leireomadina](https://codepen.io/leireomadina)
- Frontend Mentor: [@leireomadina](https://www.frontendmentor.io/profile/leireomadina)

Thank you for your time 😊
