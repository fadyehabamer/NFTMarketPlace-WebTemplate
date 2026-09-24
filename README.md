# NFTMarketPlace-WebTemplate

**PsychoArt** - a responsive, single-page NFT marketplace landing page template built with plain HTML, CSS and JavaScript.

**Live demo:** https://fadyehabamer.github.io/NFTMarketPlace-WebTemplate/

## Features

- Hero, partners, about, collections, featured artworks, top creators, FAQ and call-to-action sections
- Collection filter (All / Art / Photography / Pattern)
- Featured artwork and creator carousels powered by [Swiper](https://swiperjs.com/)
- FAQ accordion
- Responsive layout with a collapsible mobile menu

## Tech

- HTML5, CSS3, vanilla JavaScript
- [Swiper 7](https://swiperjs.com/) (via unpkg CDN)
- [Font Awesome 6](https://fontawesome.com/) (via cdnjs CDN)
- Google Fonts: Playfair Display, Poppins

## Project structure

```
index.html      # page markup
style.css       # styles
js/script.js    # menu toggle, collection filter, sliders, FAQ accordion
img/            # images and partner logos
```

## Running locally

No build step is needed. Clone the repo and open `index.html` in a browser, or serve the folder with any static server, for example:

```bash
git clone https://github.com/fadyehabamer/NFTMarketPlace-WebTemplate.git
cd NFTMarketPlace-WebTemplate
python3 -m http.server 8000
# then visit http://localhost:8000
```

An internet connection is required for the CDN-hosted Swiper, Font Awesome and Google Fonts assets.

## License

[MIT](LICENSE)
