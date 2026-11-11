# Anika Afrin — Personal Portfolio

Same Astro design as the THL portfolio, with content adapted from AAF_CV.pdf.

## Run and build

```sh
npm ci
npm run dev
npm run build
```

## Edit

- `src/content/biography.md`: introduction
- `src/content/interests.md`: research interests
- `src/content/sections/`: all sections
- `src/content/activities/`: automatically sliding activity gallery
- `src/data/profile.json`: social links
- `public/AAF_CV.pdf`: downloadable CV
- `public/profile.svg`: initials placeholder; replace with a personal photo and update the image path in `src/pages/index.astro`

## GitHub Pages

Upload this project to `anikaafrin/anikaafrin.github.io` (or the intended account's matching username.github.io repository). In Settings → Pages select GitHub Actions. The included workflow builds and deploys on pushes to main.

## Content requiring replacement

The portrait is an initials placeholder. Activity photos, locations, and optional slides/video links are missing from the CV. The IDAA presentation title is a marked sample placeholder. No Google Scholar URL was supplied. Published and ongoing research are kept separate. Undergraduate CGPA is omitted.
