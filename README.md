# KS Konnect

Static build of two KS Konnect pages, matched to the supplied mockups.

- `index.html`: home page
- `majlis.html`: Majlis membership inquiry form

`style.css` is generated from `src/style.src.css`. In the source, `Nu` means N pixels on the 853px-wide mockup and becomes `calc(N * var(--u))`, so the desktop layout keeps its proportions at any width up to 1100px. Phones get a single-column layout.

The founders portrait (`img/home-hero.jpg`) and the Majlis event photo (`img/majlis-event.jpg`) are the client's photos.

The home page has a play button over the founders portrait. Clicking it (or anywhere on the photo) opens the KS Konnect corporate trailer (`video/ks-konnect-trailer.mp4`, 720p) in a lightbox with sound and player controls. `img/trailer-poster.jpg` is its closing frame, shown before playback starts.

Inquiries from the Majlis form are emailed through FormSubmit (formsubmit.co), using the inbox's FormSubmit code rather than the address itself. Each inquiry is also copied to sarah@mavenmarketingandevents.com.

The site is deployed on Vercel from the `main` branch.
