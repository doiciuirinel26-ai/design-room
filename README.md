# RoomVibe 3D

A browser-based 3D room designer and viewer built with Three.js.

## Features

- Interactive 3D room viewer with WASD navigation
- 2D room layout editor with drag-and-drop furniture placement
- Export room layouts to 3D view
- Support for custom 3D assets in GLB format

## 3D Assets

All GLB model files are stored in the [`assets/`](./assets/) folder.

To use a model in the app, upload your `.glb` file to `assets/` and reference it via its raw GitHub URL:

```
https://raw.githubusercontent.com/doiciuirinel26-ai/design-room/main/assets/YOUR_FILE.glb
```

## Project Structure

```
design-room/
├── assets/          ← upload your .glb 3D models here
├── roomvibe-v7.html ← 2D room editor
├── roomvibe-3d.html ← 3D viewer
└── README.md
```

## Usage

Open `roomvibe-v7.html` in a browser to use the room editor.  
Click **View in 3D** to launch the 3D viewer (`roomvibe-3d.html`).
