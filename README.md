# FrameIt Website

A single-page static portfolio website for FrameIt, built with plain HTML, CSS, and JavaScript.

## Structure

- `FrameIt_Website.html` — main landing page and interactive experience.
- `assets/` — folder containing image assets used by the gallery, hero sections, and inspiration strip.

## Features

- Responsive hero section with call-to-action buttons
- Gallery with frame previews and lightbox interaction
- Interactive customizer section for previewing framed artwork
- Dynamic asset library rendered from local files
- Styled to resemble framed wall art

## How to use

1. Open `FrameIt_Website.html` in a web browser.
2. Ensure the `assets/` folder remains in the same directory as the HTML file.
3. For local development, open the file directly or serve it from a static server.

## Local preview

To run a local preview from the project folder, you can use a simple HTTP server. For example:

```bash
cd /Users/mac/Desktop/website
python3 -m http.server 8000
```

Then open `http://localhost:8000/FrameIt_Website.html` in your browser.

## Notes

- No build step is required.
- The page uses inline CSS and JavaScript.
- Keep `assets/` with the HTML file so images load correctly.
