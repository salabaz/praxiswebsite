# Self-Hosted Fonts

This directory contains self-hosted WOFF2 font files to avoid external requests to fonts.google.com.

## Required Files

Download these files and place them in this directory:

1. **playfair-display-400-latin.woff2**
   - Source: https://fonts.gstatic.com/s/playfairdisplay/v40/nuFiD-vYSZviVYUb_rj3ij__anPXDTzYgA.woff2
   - Weight: 400 (Regular)
   - Unicode range: Latin

2. **playfair-display-700-latin.woff2**
   - Source: https://fonts.gstatic.com/s/playfairdisplay/v40/nuFvD-vYSZviVYUb_rj3ij__anPXJzDYgA.woff2
   - Weight: 700 (Bold)
   - Unicode range: Latin

## How to Download

1. Open the URLs above in your browser
2. Save the files with the exact names specified above
3. Place them in this directory
4. Commit and push the changes

## Reference

These fonts are referenced in `assets/css/_fonts.scss` with @font-face rules.
