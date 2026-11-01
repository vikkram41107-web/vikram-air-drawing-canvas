# 🌟 AIR CANVAS AI
> *"Your Hand Is the Brush. The Air Is Your Canvas."*

A full-screen, webcam-driven AI air drawing experience. Open your browser, look directly at yourself on screen, and paint glowing neon artwork directly in thin air using real-time hand tracking.

---

## 🎯 How It Works

1. **Full-Screen Live Camera**: Your webcam feed occupies the entire viewport, mirrored naturally like a mirror.
2. **Finger-Only Drawing**:
   - ☝️ **Point 1 Index Finger**: **Draw Mode** — glide your fingertip through the air to produce continuous glowing neon strokes.
   - ✌️ **Two Fingers (Peace Sign)**: **Hover Mode** — move the targeting cursor across the screen to reposition without drawing lines.
   - ✊ **Closed Fist / Relaxed Hand**: **Pause / Stop** — safely breaks active strokes.
3. **No Mouse Drawing**: Clicking or dragging with the mouse will never draw on the canvas. Drawing is controlled exclusively by your physical index finger.
4. **Minimal Floating HUD**: A sleek, semi-transparent top bar houses color swatches, brush sizing, eraser, undo, redo, clear, and export without obstructing your drawing space.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| <kbd>B</kbd> | Brush Mode |
| <kbd>E</kbd> | Eraser Mode |
| <kbd>Ctrl</kbd> + <kbd>Z</kbd> | Undo Last Stroke |
| <kbd>Ctrl</kbd> + <kbd>Y</kbd> / <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Z</kbd> | Redo Stroke |
| <kbd>C</kbd> | Clear Canvas (with confirmation) |
| <kbd>G</kbd> | Toggle Alignment Grid |
| <kbd>H</kbd> | Toggle 21-Joint Hand Skeleton |
| <kbd>Ctrl</kbd> + <kbd>S</kbd> | Export Artwork as PNG |

---

## 🛠️ Technology Stack

- **Frontend**: React 19, TypeScript, Vite
- **Computer Vision**: `@mediapipe/tasks-vision` (HandLandmarker with local Float16 model asset)
- **Drawing Engine**: HTML5 Canvas API (High-DPI scaled, Bezier curve smoothing, neon glow shaders)
- **Styling**: Vanilla CSS3 (Full-screen viewport, translucent glassmorphism)
- **Icons**: Lucide React

---

## 🏁 Quickstart

```bash
# 1. Install dependencies
npm install

# 2. Run local dev server
npm run dev
```

Open [http://localhost:5176](http://localhost:5176) in Google Chrome, Microsoft Edge, or Brave. Allow camera permissions when prompted, raise your hand, point your index finger, and start air drawing!
