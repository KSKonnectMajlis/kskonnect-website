# KS Konnect

Static build of two KS Konnect pages, matched to the supplied mockups.

- `index.html`: home page
- `majlis.html`: The KS Konnect Majlis, "Express your interest" form

`style.css` is generated from `src/style.src.css`. In the source, `Nu` means N pixels on the 853px-wide mockup and becomes `calc(N * var(--u))`, so the desktop layout keeps the mockup's proportions at any width up to 1280px. Phones get a single-column layout.

The founders portrait (`img/home-hero.jpg`, `img/majlis-hero.jpg`) and the Majlis event photo (`img/majlis-event.jpg`) are the client's photos. The portrait is cut out and placed on the dark background at the mockup's position.
