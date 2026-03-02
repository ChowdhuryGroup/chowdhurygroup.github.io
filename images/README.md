# Project Images

Drop image files here (PNG, JPG, GIF, WebP, SVG) and reference them in `projects.json`.

## How to add an image to a project

1. Copy your image file into this directory, e.g. `spotgauge-screenshot.png`
2. Open `projects.json` and set the `"image"` field for that project to the filename:

```json
"image": "images/spotgauge-screenshot.png"
```

The landing page will automatically show the image on the project card.
Leave `"image"` as an empty string `""` to show no image.

## Recommended sizes

| Usage | Recommended size |
|---|---|
| Featured project (SpotGauge hero) | 1200 × 675 px (16:9) |
| Project card thumbnails | 600 × 340 px (16:9) |
