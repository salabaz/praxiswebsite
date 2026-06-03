# Self-Hosted Fonts

This directory contains self-hosted WOFF2 font files to avoid external requests to fonts.google.com.

## Required File

**Playfair Display uses a variable font** where both weights (400 Regular and 700 Bold) are included in a single WOFF2 file.

Download this file and place it in this directory:

### playfair-display-latin.woff2
- **Source:** https://fonts.gstatic.com/s/playfairdisplay/v40/nuFiD-vYSZviVYUb_rj3ij__anPXDTzYgA.woff2
- **Contains:** Weights 400 (Regular) and 700 (Bold)
- **Unicode range:** Latin

## How to Download

1. Open the URL above in your browser
2. Save the file as `playfair-display-latin.woff2`
3. Place it in this directory
4. Commit and push the changes

## Reference

This font is referenced in `assets/css/_fonts.scss` with a single @font-face rule that covers both weights (400 700).

## Note

Google Fonts serves Playfair Display as a variable font. The single WOFF2 file contains both the Regular (400) and Bold (700) weights, which is why the original Google Fonts CSS had the same URL for both @font-face rules.
