# Optic Homes — AI Virtual Try-On V2

## Main fix

The previous version started the camera and AI engine together with `Promise.all`.
When the AI package failed to load, it incorrectly displayed a camera error even
though the camera was already working.

V2 starts the camera first and loads AI separately.

## Improvements

- Correct camera-vs-AI error handling
- Uses the official current MediaPipe Tasks bundle
- Pinned MediaPipe Tasks fallback
- Backup CDN
- Legacy MediaPipe Face Mesh fallback
- Manual drag-and-resize fallback if every AI CDN fails
- Camera remains visible while AI loads
- More resilient camera constraints
- Better loading states and exact error messages
- AI engine status chip
- Fit quality score
- Recenter control
- Improved mobile and desktop try-on UI
- Smoother frame tracking and fitting
- Photo capture and Add to Cart remain included

## Deploy

Replace the existing repository `index.html` with the new one in this folder.
Keep `.nojekyll` in the repository root and commit the changes.

After GitHub Pages updates, hard refresh:

- Windows/Chrome: `Ctrl + Shift + R`
- Mobile Chrome: open the site in an Incognito tab once to bypass the old cache.
