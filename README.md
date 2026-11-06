# MIRL Map landing page

A single page (`index.html`, no build, nothing loaded from another service) that
introduces the MIRL Map platform and sends visitors to "Create your own map".
Its typefaces are vendored in `fonts/` (SIL Open Font License, texts alongside),
and it shares the design of the other MIRL tools.

## Hosting it at mirl-map.mirl.arthistory.ucsb.edu

Two easy options:

**A. UCSB web hosting.** Upload `index.html`, `favicon.svg`, `fonts/`, and
`images/` to wherever `mirl-map.mirl.arthistory.ucsb.edu` is served from.

**B. GitHub Pages with the custom domain.**
1. Put these files in a repo (for example `mirl-ucsb/mirl-map-landing`) and push.
2. In the repo's Settings > Pages, set the source to the `main` branch.
3. Add a `CNAME` file containing `mirl-map.mirl.arthistory.ucsb.edu` (it is left
   out while the page is served at `mirl-ucsb.github.io/mirl-map-landing/`), and
   ask UCSB IT to add a DNS record pointing that subdomain to GitHub Pages (a
   CNAME record to `mirl-ucsb.github.io`).

## Editing

Open `index.html` and edit the text. The "Create your own map" buttons link to
the MIRL Map service at `https://mirl-map-auth.mirl-ucsb.workers.dev/create`,
which signs the visitor in with GitHub and makes their copy, and "See a live
example" links to `https://mirl-ucsb.github.io/mirl-map-example/`. Update them if
your addresses differ. `images/example.jpg` is a screenshot of that example.
