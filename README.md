# Frontend Mentor - NFT preview card component solution

This is my solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

## Links

- Live site URL: [NFT preview card component](https://melissavi08.github.io/nft-preview-card-component/index.html)

## Built with

<img alt='HTML5' src='https://img.shields.io/badge/HTML-100000?style=flat&logo=HTML5&logoColor=white&labelColor=F77421&color=F77421'/> <img alt='CSS3' src='https://img.shields.io/badge/CSS_Custom_Properties-100000?style=flat&logo=CSS3&logoColor=white&labelColor=00BFFF&color=00BFFF'/> <img alt='Flexbox' src='https://img.shields.io/badge/Flexbox-100000?style=flat&logo=&logoColor=white&Color=D063E4&color=D063E4'/> <img alt='Flexbox' src='https://img.shields.io/badge/CSS_Grid-100000?style=flat&logo=&logoColor=white&Color=D063E4&color=47DAB2'/> <img alt='Responsive_Desing' src='https://img.shields.io/badge/Responsive_Desing-100000?style=flat&logo=&logoColor=white&Color=FF69B4&color=FF69B4'/>

## What I learned

For this project my main challenge was the image overlay in hover state, I used [W3shool](https://www.w3schools.com) resources to get this solution, concretely [How TO - Image Hover Overlay](http://www.w3schools.com/howto/howto_css_image_overlay.asp).
To see how I solved it you can see below 👇

#### HTML code

```html
<figure class="card-image">
  <img src="./images/image-equilibrium.jpg" alt="equilibrium" />
  <div class="card-image-overlay"></div>
</figure>
```

#### CSS code

```css
:root {
  --cyan-overlay: #00fff780;
}

.card-image {
  position: relative;
  width: 270px;
  height: 270px;
  border-radius: 10px;
  overflow: hidden;
}

.card-image img {
  width: 100%;
}

.card-image-overlay {
  position: absolute;
  top: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
  background-image: url(../images/icon-view.svg);
  background-position: center;
  background-repeat: no-repeat;
  transition: 0.5s ease;
}

.card-image-overlay:hover {
  cursor: pointer;
  opacity: 1;
  background-color: var(--cyan-overlay);
}
```

## Useful resources

<a href='https://www.w3schools.com/' target="_blank"><img alt='GitHub' src='https://img.shields.io/badge/W3schools-100000?style=flat&logoColor=white&color=04aa6d'/></a>

## Connect with me

<a href='https://twitter.com/melissa_vi2' target="_blank"><img alt='Twitter' src='https://img.shields.io/badge/melissa__vi2-100000?style=flat&logo=Twitter&logoColor=white&labelColor=00BFFF&color=FF69B4'/></a> <a href='https://www.linkedin.com/in/melissa-villegas' target="_blank"><img alt='LinkedIn' src='https://img.shields.io/badge/Melissa_Villegas-100000?style=flat&logo=LinkedIn&logoColor=white&labelColor=00BFFF&color=FF69B4'/></a>
