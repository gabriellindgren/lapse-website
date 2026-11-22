# Lapse Website
Static website for the iOS app `Lapse`.

## Structure
- `index.html`, `privacy.html`, and `contact.html` are the site pages.
- `styles.css` contains shared styles (light and dark); `site.js` adds the header hairline and scroll reveals.
- `images/branding` contains logo and favicon assets.
- `images/app` holds the app's `tools/screenshots` raw captures placed inside Apple's official product bezels (iPhone 17 Pro Max Silver and Deep Blue, iPad Pro 13" Space Black, iPhone Duo Night Sky), as AVIF with a PNG fallback. Keep both sides of each image an even number of pixels: Chrome decodes odd-sized AVIFs with transparency as blank. `images/og.jpg` is the link preview.
