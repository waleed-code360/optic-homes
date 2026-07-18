# Optic Homes — Real Frame Overlay Fix

This version fixes the virtual try-on so the real uploaded frame images are
used on the face instead of the stylized AI-drawn frame.

## Included
- 3 transparent PNG cutouts made from the real uploaded sunglasses photos
- Each product now has an `overlayImage`
- Try-on uses the real frame overlay directly
- Stylized vector frame remains only as a fallback

## Deploy
Replace the current `index.html` in your GitHub Pages repo with this file and keep `.nojekyll`.
