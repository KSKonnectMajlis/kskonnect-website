# KS Konnect

Static build of two KS Konnect pages, matched to the supplied mockups.

- `index.html`: home page
- `majlis.html`: Majlis membership inquiry form

`style.css` is generated from `src/style.src.css`. In the source, `Nu` means N pixels on the 853px-wide mockup and becomes `calc(N * var(--u))`, so the desktop layout keeps its proportions at any width up to 1100px. Phones get a single-column layout.

The founders portrait (`img/home-hero.jpg`) and the Majlis event photo (`img/majlis-event.jpg`) are the client's photos. The portrait is cut out and placed on the dark background at the mockup's position.
