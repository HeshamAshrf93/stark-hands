# stark-hands

Grab, rotate, zoom and take apart 3D models with your bare hands, using a normal webcam. No gloves, no special hardware.

> Status: early development.

## Planned features

- [ ] Real-time hand tracking in the browser (MediaPipe Hands)
- [ ] 3D scene with Three.js
- [ ] Gestures: pinch to grab, two-hand pinch to zoom, rotate with wrist, open palm to release
- [ ] "Explode" a model into its parts and put it back together
- [ ] Load any glTF / GLB model
- [ ] Gesture smoothing to stop jitter
- [ ] Works on a laptop webcam at 30+ FPS
- [ ] Gesture events API so other apps (voice, hologram display) can plug in
- [ ] Automated tests for the gesture logic using recorded landmark data (no video of people)

## Planned usage

```bash
npm install
npm run dev
```

Open the page, allow the camera, and use your hands.

## Roadmap

1. Project setup: Vite, Three.js, tests, CI
2. Hand tracking
3. Grab and move
4. Rotate and zoom
5. Explode / assemble models
6. Smoothing and performance
7. Gesture events API
8. Docs and live demo

## Privacy

Camera frames are processed locally in the browser and are never uploaded.

## License

MIT, see [LICENSE](LICENSE).

---
Built by [Hesham Ashraf](https://www.linkedin.com/in/hesham-ashrf)
