# Pencil 3D

![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)

A Pen created on CodePen.

Original URL: [https://codepen.io/markmanx01/pen/yJJxRj](https://codepen.io/markmanx01/pen/yJJxRj).

I was interested to see how a Material design inspired UI could be enhanced with a 3D object, in this case the pencil is rendered as a 3D object, but still manages to look like it fits in with the flat style.

The shadow and sketch are rendered on a separate 2D canvas (using paper.js vector graphics library), while the pencil is rendered on its own canvas with THREE.js.

## Features
- 3D pencil follows your mouse cursor
- Draw freely on the sketchpad with smooth vector strokes
- Clear button to reset the canvas
- Responsive layout

## Tech Stack
- [Three.js](https://threejs.org/) — 3D pencil rendering
- [Paper.js](http://paperjs.org/) — 2D vector drawing
- [GSAP / TweenMax](https://greensock.com/gsap/) — animations

## Run Locally
Open `index.html` directly in your browser — no build step required.

## Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `Escape` | Clear the canvas |
| `Ctrl + Z` | Undo last stroke |