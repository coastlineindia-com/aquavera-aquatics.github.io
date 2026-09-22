# AQUAVERA Image Sources

The visual assets in this demo were created for the storefront presentation and locally packaged into the ZIP. Product images are assigned deterministically to specific catalog items. No product card depends on a remote image URL.

## Image handling
- Product photography is stored under `assets/images/products/`.
- Category photography is stored under `assets/images/categories/`.
- The hero image is stored under `assets/images/hero/`.
- Images are locally referenced so the storefront can be uploaded to GitHub Pages without external image dependencies.

## Presentation rule
Product cards use `object-fit: contain` and dedicated image boxes so products remain completely visible instead of being aggressively cropped.
