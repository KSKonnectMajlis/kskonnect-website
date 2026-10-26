# KS Konnect

Static build of two KS Konnect pages, matched to the supplied mockups.

- `index.html`: home page
- `majlis.html`: Majlis membership inquiry form

`style.css` is generated from `src/style.src.css`. In the source, `Nu` means N pixels on the 853px-wide mockup and becomes `calc(N * var(--u))`, so the desktop layout keeps its proportions at any width up to 1100px. Phones get a single-column layout.

The founders portrait (`img/home-hero.jpg`) and the Majlis event photo (`img/majlis-event.jpg`) are the client's photos.

The home page opens with the KS Konnect corporate trailer, muted and looping, with a sound button. `video/ks-konnect-trailer.mp4` is the 720p web version and `video/ks-konnect-trailer-360.mp4` is served to phones. The founders portrait shows until the video starts.

Inquiries from the Majlis form are emailed through FormSubmit (formsubmit.co). The first submission sends an activation email to the inbox, and forms only deliver after that link is clicked.

The site is deployed on Vercel from the `main` branch.
