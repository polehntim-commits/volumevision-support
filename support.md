---
layout: default
title: Support — Volume Vision
---

# Support

## Getting Started

Volume Vision requires an iPhone or iPad with a LiDAR sensor. The app also runs on Mac as "Designed for iPad."

1. **Capture** — Point your device at an object and tap to capture RGB and LiDAR depth data.
2. **Annotate** — Draw bounding boxes or polygon masks around objects of interest.
3. **Train** — Configure your model settings and train directly on-device. No internet required.
4. **Export** — Save trained models as CoreML for use in your own applications.

## Tips

- Start with 20–30 annotated captures before your first training run.
- Use the Delta Depth input channel for structural features that RGB may miss.
- Training runs best on iPad with longer battery life and thermal headroom.
- Monitor the thermal indicator during training — the app will automatically throttle if your device gets warm.

## Known Limitations

- LiDAR capture requires a device with a LiDAR sensor (iPhone 12 Pro and later, iPad Pro 2020 and later).
- On Mac, LiDAR capture is unavailable. You can annotate and train using previously captured data.
- Training complex models with many classes may take several hours.

## Contact

For bug reports, feature requests, or questions:
polehntim@gmail.com
