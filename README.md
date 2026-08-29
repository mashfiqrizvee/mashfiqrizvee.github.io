# Md Mashfiq Rizvee — Academic Portfolio v2

This is the deployed academic portfolio for `https://mashfiqrizvee.github.io`.

The layout follows the visual rhythm of Aiman Rahman's academic site while keeping the content focused on Mashfiq's research profile.

## GitHub Pages

Keep GitHub Pages configured as:

- Branch: `main`
- Folder: `/(root)`

## Replacing the dummy images

The website intentionally displays `images/placeholder.svg` wherever a future image belongs. You **do not need to edit `index.html`** when replacing them.

Upload your real image files into the `images/` folder using exactly these filenames:

| File | What to upload | Recommended shape |
|---|---|---|
| `images/profile-photo.jpg` | Professional headshot/portrait | Portrait, about 4:5 |
| `images/jumio-logo.png` | Jumio logo | Wide, transparent PNG |
| `images/ku-logo.png` | University of Kansas logo | Wide, transparent PNG |
| `images/texas-tech-logo.png` | Texas Tech University logo | Wide, transparent PNG |
| `images/publication-1.png` | Figure/teaser for Open-Set Biometric Watchlist | Landscape, about 16:9 |
| `images/publication-2.png` | Figure/teaser for Bio-BloomChain | Landscape, about 16:9 |
| `images/publication-3.png` | Figure/teaser for Persistent HBF / IC authentication | Landscape, about 16:9 |
| `images/publication-4.png` | Figure/teaser for Dynamic HBF / biometric authentication | Landscape, about 16:9 |
| `images/teaching-logo.png` | KU EECS or KU logo | Square or transparent logo |

A small JavaScript helper tests for those filenames at page load. If the real file exists, it automatically replaces the dummy image.

For publication cards, a framework diagram, graphical abstract, or representative results figure will usually look better than a screenshot of the paper's first page.
