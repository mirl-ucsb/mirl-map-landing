# MIRL Map landing page

A single self-contained page (`index.html`, no dependencies, no build) that
introduces the MIRL Map platform and sends visitors to "Create your own map"
(GitHub's template-generate flow for `mirl-ucsb/mirl-map`).

## Hosting it at mirl-map.mirl.arthistory.ucsb.edu

Two easy options:

**A. UCSB web hosting.** Upload `index.html` to wherever
`mirl-map.mirl.arthistory.ucsb.edu` is served from. That is it.

**B. GitHub Pages with the custom domain.**
1. Put these files in a repo (for example `mirl-ucsb/mirl-map-landing`) and push.
2. In the repo's Settings > Pages, set the source to the `main` branch.
3. The included `CNAME` file already points the site at
   `mirl-map.mirl.arthistory.ucsb.edu`. Ask UCSB IT to add a DNS record so that
   subdomain points to GitHub Pages (a CNAME record to `mirl-ucsb.github.io`).

## Editing

Open `index.html` and edit the text. The "Create your own map" button links to
`https://github.com/mirl-ucsb/mirl-map/generate`, and "See a live example" links
to `https://mirl-ucsb.github.io/mirl-map/` (enable Pages on the mirl-map repo to
make that live). Update both if your addresses differ.
