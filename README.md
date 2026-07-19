# Optic Homes — Free 3D Try-On

This build uses the existing free MediaPipe face tracking and a custom
3D-like procedural eyewear renderer.

Main changes:
- no paid SDK
- no product-photo background boxes in live try-on
- stable frame shapes
- product-specific lenses and materials
- bridge, hinges, reflections and side temples
- perspective response when the head turns
- manual scale and vertical fit controls remain available

Deploy:
1. Replace the repository root index.html with this file.
2. Keep .nojekyll in the root.
3. Commit and hard-refresh the GitHub Pages website.
