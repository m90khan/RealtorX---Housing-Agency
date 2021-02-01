### Realtor - FrontEnd Single Page Website

<br />
<p align="center">
  <a href="https://m90khan.github.io/RealtorX---Housing-Agency/">
    <img src="./img/favicon.png" alt="Logo" width="120" height="120">
  </a>

  <h3 align="center">RealtorX - Front End </h3>

  <p align="center">
Listings Website <br />
    <a href="m90khan@gmail.com"><strong>Contact Me</strong></a>
    <br />
    <br />
    <a href="https://m90khan.github.io/RealtorX---Housing-Agency/">View Demo</a>
    
   </p>
</p>

## Table of Contents

- [About the Project](#about-the-project)
- [Skills](#skills)
- [Code Snipet](#code)
- [Contact](#Contact)

---

### About the Project

- Realtor Listing Website for the real estate agents

Scripts:
run npm install for node-modules installation
"start": "npm-run-all --parallel devserver watch:sass",
"build:css": "npm-run-all compile:sass concat:css prefix:css compress:css"

Layout: CSS Grid Layout (BEM Model)

Live: https://m90khan.github.io/RealtorX---Housing-Agency/

<img src="./img/realtorx.gif" alt="" />
<img src="./img/desktop-view.jpg" alt="" />

---

### Skills

[<img align="left" alt="Visual Studio Code" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />][youtube]
[<img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />][youtube]
[<img align="left" alt="CSS3" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />][youtube]
[<img align="left" alt="Sass" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sass/sass.png" />][youtube]
[<img align="left" alt="Git" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />][youtube]
[<img align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />][youtube]
[<img align="left" alt="Terminal" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" />][youtube]
<br />
<br />

---

### Code Snippet

```scss
.realtors {
  background-color: $color-secondary;
  grid-column: col-start 7 / full-end;
  padding: 3rem;

  display: grid;
  align-content: center;
  justify-content: center;
  grid-row-gap: 3rem;
  justify-items: center;
  @media only screen and (max-width: $bp-medium) {
    grid-column: 1 / -1;
  }

  &__list {
    display: grid;

    grid-template-columns: min-content max-content;

    grid-column-gap: 2rem;
    grid-row-gap: 5vh;
    align-items: center;
    @media only screen and (max-width: $bp-medium) {
      grid-template-columns: repeat(3, min-content max-content);
    }

    @media only screen and (max-width: $bp-small) {
      grid-template-columns: min-content max-content;
    }
  }
  &__img {
    width: 7rem;
    border-radius: 50%;
  }
  &__details {
  }
  &__sold {
    text-transform: uppercase;
    color: $color-grey-light-2;
    margin-top: -3px;
  }
}
```

---

### Connect with me:

[<img align="left" alt="Khan | YouTube" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />][youtube]

[<img align="left" alt="twitter | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="khanmohsinx | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="khanuxd | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]
<br />

---

[youtube]: https://www.youtube.com/channel/UC96rVfdTKsjZpREnH6CaCOw
[twitter]: https://twitter.com/m90khan
[linkedin]: www.linkedin.com/in/uxdkhan
[instagram]: https://www.instagram.com/uxd.khan/
