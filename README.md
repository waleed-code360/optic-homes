# Optic Homes — Three.js Virtual Try-On

This build replaces the procedural 2D canvas frame with a genuine Three.js
WebGL eyewear model.

Features:
- Three.js r184 WebGL renderer
- real extruded frame rims
- transparent lens meshes
- three-dimensional bridges and hinges
- curved temples extending behind the front frame
- natural Y-axis head-turn perspective
- product-specific geometry for seven frame styles
- MediaPipe tracking retained
- photo capture includes the WebGL overlay
- automatic 2D fallback if Three.js cannot load

Deployment:
1. Replace the repository root index.html with this file.
2. Keep .nojekyll in the repository root.
3. Commit and hard-refresh the GitHub Pages website.
