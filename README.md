# Universe Animation

![Universe Animation Screenshot](https://raw.githubusercontent.com/BinaryVortex/Universe-Animation/main/Screenshot%202024-08-22%20184444.png)

Universe Animation built using HTML, CSS and JavaScript — a lightweight Three.js scene that renders a rotating starfield and a pulsating nucleus using simplex noise.

## Demo

Open `index.html` in your browser (or use VS Code Live Server / any static file server) to see the animation.

## Features

- Interactive 3D scene powered by Three.js
- Procedurally deformed nucleus using Simplex Noise
- Moving and fixed star layers with additive blending
- Orbit controls with auto-rotate for smooth camera motion
- Background skybox texture for depth and atmosphere

## Technologies

- HTML, CSS, JavaScript
- Three.js (r0.121.1)
- Simplex-noise

## How to run

1. Clone the repository:

   git clone https://github.com/BinaryVortex/Universe-Animation.git

2. Open the project folder and open `index.html` in your browser.

   - For best results use a local static server (e.g. VS Code Live Server) to avoid cross-origin issues when loading textures.

## Controls

- Click and drag to orbit the camera.
- Scroll to zoom (OrbitControls limits are set to keep you near the scene).
- The camera auto-rotates by default.

## Customize

- Tweak `blobScale` in `index.html` to increase/decrease nucleus deformation.
- Change textures by editing the TextureLoader URLs near the top of `index.html`.
- Adjust lights, particle counts, or camera settings in `index.html`.

## Assets

This project loads a few external textures. You can replace them with local files if you prefer:

- Background: https://i.ibb.co/4gHcRZD/bg3-je3ddz.jpg
- Nucleus: https://i.ibb.co/hcN2qXk/star-nc8wkw.jpg
- Star sprites: https://i.ibb.co/ZKsdYSz/p1-g3zb2a.png, https://i.ibb.co/F8by6wW/p2-b3gnym.png, https://i.ibb.co/yYS2yx5/p3-ttfn70.png, https://i.ibb.co/yWfKkHh/p4-avirap.png

## Notes

- The repository currently has no explicit license. Add a LICENSE file if you want to specify usage rights.

## Credits

Built by BinaryVortex — feel free to open issues or submit improvements.
