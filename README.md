# Hemal Variya — Portfolio & CV

Modern, lightweight portfolio hosted on GitHub Pages with an embedded CV.

## Live Links

- Home: https://variyahemal.github.io/ (if configured as a user site)
- Project site (alternative): https://variyahemal.github.io/hemalvariya.github.io/
- CV page: Append `cv.html` to the base, e.g. `.../cv.html`

## Features

- Clean homepage with gradient header and subtle animations.
- CV page renders the PDF via an iframe with a graceful fallback.
- Buttons to download or open the PDF in a new tab.
- Works on GitHub Pages without server-side code.

## Add Your CV

Place your file at the repository root with this exact name:

- `Hemal_Variya_CV.pdf`

Then commit and push.

## Local Preview

```bash
python -m http.server 8000
# Visit http://localhost:8000/
```

## Deploy

```bash
git add .
git commit -m "Update UI and CV iframe"
git push
```

Ensure GitHub Pages is enabled in the repository settings. For a user site, the repo name must match your username: `variyahemal.github.io`.