# Tharaka & Nipuni — Wedding Invitation

A single-page wedding invitation site for the homecoming celebration of
Tharaka & Nipuni — 14 November 2026, Tropical Life Resort & Spa, Dambulla.

## Structure

- `index.html` — the whole site (styles and scripts are inline)
- `assets/photos/` — couple photographs: the "Captured moments" gallery,
  plus `couple-hero-glow.jpg` used as the soft ambient backdrop in the hero
  (shown at low opacity with a slow zoom)
- Root media files (`*.png`, `*.jpg`, `*.jpeg`, `*.mp4`) — decorative artwork
  referenced by `index.html`

## Preview

Open `index.html` in a browser, or serve the folder with any static server:

```sh
python3 -m http.server 8000
```

## Adding more photos

1. Save the file as `assets/photos/<short-description>.jpg` (lowercase, hyphens).
2. Keep it under ~200 KB and strip camera metadata before committing.
3. Add a `<figure class="photo">` block inside the `#gallery` section of
   `index.html`, following the existing pattern.
