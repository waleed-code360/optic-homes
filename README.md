# Optic Homes — Live AI Virtual Try-On

## What was added

- Live front-camera virtual eyewear try-on
- Google MediaPipe AI face landmark tracking
- Real-time tracking of eyes, nose, face width, head tilt and left/right turn
- 3D-style frame depth, temples, lens tint, reflections and frame materials
- Try On buttons on every product
- Full-screen mobile-first try-on experience
- Switch between all products without closing the camera
- Frame size and vertical-fit adjustments
- Camera switching
- Try-on photo capture
- Add to Cart directly from the try-on screen
- Privacy notice: camera frames are processed in the browser

## Deploy

Replace the old repository `index.html` with this one and keep `.nojekyll`
in the repository root. GitHub Pages must use HTTPS for camera access.

## Internet requirement

The AI model and MediaPipe browser runtime are loaded from official Google
model hosting and jsDelivr. The site therefore needs an internet connection
when the virtual try-on is first opened.

## Product assets

The current catalogue uses demo frame designs. For final inventory, replace
the demo products with real transparent product assets and exact frame
measurements. The live tracking system will continue to work.
