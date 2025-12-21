# goit-markup-hw-04

**Homework #4:** Layout page with icons and decorative effects.

Set up GitHub Pages and add a link to the live page in the **About** section of the repository.

---

## A — Project

- **A1** — The project root contains an `images/` folder with images.
- **A2** — All vector images (icons) are collected in an SVG sprite `icons.svg` located in the `images/` folder.
- **A3** — All vector images are optimized.
- **A4** — The project root contains a `css/` folder with the stylesheet.
- **A5** — All styles are written in a single `styles.css` file inside the `css/` folder.
- **A6** — File names contain **no uppercase letters, spaces, or transliteration**; only lowercase English letters and words.
- **A7** — Code formatted using **Prettier**.
- **A8** — All images and text content are taken from the design layout. Code follows the [Code Guide](https://codeguide.co/) recommendations.
- **A9** — [modern-normalize](https://cdnjs.com/libraries/modern-normalize) is included.
- **A10** — SVG sprite generated using [Icomoon](https://icomoon.io/).
- **A11** — Generated SVG sprite optimized using [SVGOMG](https://jakearchibald.github.io/svgomg/).
- **A12** — Code follows best practices.

---

## B — Markup

- **B1** — All icons use vector graphics in SVG format.
- **B2** — SVG icons are exported correctly; “group” option is used, not the raw vector.
- **B3** — All icons from the SVG sprite are added in HTML using `<svg>` and `<use>`.
- **B4** — In the “Advantages” section (unnamed section above Our Team), icons are included.
- **B5** — In the Our Team section, social media icons are included.
- **B7** — Social media icons are added in the footer.
- **B8** — Full HTML markup of all layout elements is completed.
- **B9** — Tags are used according to their semantic meaning.

---

## C — Visual Design & Effects

- **C1** — Large image with darkening effect (under header) is implemented as a background. Gradient layered background is used for darkening.
- **C2** — Background image in the block under header does not stretch beyond its original 1440px width.
- **C3** — Cards in the Our Team section have a permanent shadow effect.
- **C4** — Cards in the Our Portfolio section have a hover shadow effect anywhere on the card.
- **C5** — On hover or focus, icons change to an active state (color change if specified in layout).
- **C6** — All hover and focus effects (color, background, shadow) have transitions: duration 250ms, timing function `cubic-bezier(0.4, 0, 0.2, 1)`.
- **C7** — Transitions explicitly define animated properties; `all` is not used.
- **C8** — In main navigation, the current page link is underlined using `::after` pseudo-element.
- **C9** — Overlay with text on Our Portfolio cards appears on hover anywhere on the card.
- **C10** — Blue overlay on Our Portfolio cards slides up from the bottom.
- **C11** — Pseudo-elements do not have text content in `content`; used purely for decorative purposes.

---

## Resources

- [Code Guide](https://codeguide.co/) — coding style guide
- [modern-normalize](https://cdnjs.com/libraries/modern-normalize) — CSS normalization
- [Icomoon](https://icomoon.io/) — SVG sprite generation
- [SVGOMG](https://jakearchibald.github.io/svgomg/) — SVG optimization

---

**Live page:** [GitHub Pages](https://akinaru72.github.io/goit-markup-hw-04/)
