# PIP Electrics — Logo Pack

## Main logo files
- `pip-electrics-logo-transparent.png` — high-res, transparent background. Use this for most things (website header, documents, dark/light backgrounds).
- `pip-electrics-logo-cream-bg.png` — same logo on its original cream background. Use when transparency isn't supported or you want the branded cream card look.
- `logo-hires-transparent.png` / `logo-hires-cream-bg.png` — same as above, full resolution, for print or large use.
- `logo-web-header-200h.png` — pre-sized to 200px tall, ready to drop straight into a website navbar.

## Favicons (browser tab icon)
- `favicon.ico` — multi-size (16/32/48px), use this as your main `favicon.ico` in the site root.
- `favicon-16x16.png`, `favicon-32x32.png`, `favicon-48x48.png` — individual PNG sizes if your setup wants separate files.
- `favicon-192x192.png`, `favicon-512x512.png` — Android/Chrome home screen icons (used in `manifest.json`).

## Apple / iOS
- `apple-touch-icon-180x180.png` — for iPhone/iPad "Add to Home Screen" icon. Has a solid cream background (Apple doesn't support transparency here).

## Social media
- `social-profile-800x800.png` — square profile picture with cream background (Facebook, Instagram, LinkedIn, Google Business Profile).
- `social-profile-transparent-800x800.png` — same, transparent, in case a platform supports it or for overlay use.

## Basic HTML snippet for favicons
```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">
<link rel="icon" type="image/png" sizes="192x192" href="/favicon-192x192.png">
```

## Note
These were generated from your existing logo image (cropped and background-removed), not redesigned. If you ever want a vector (SVG) version for perfectly crisp scaling at any size, that would need to be redrawn/traced by a designer — happy to point you toward that if needed.
