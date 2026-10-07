# Construction Lines

Point your phone camera at a product, take a photo, and see the construction lines an artist would sketch first: 3D bounding box, vanishing points, horizon line, perspective grid, centerline and ellipse guides.

## Deploy

1. Push this folder to a GitHub repository (keep `index.html` at the repo root).
2. In Vercel: **Add New → Project → Import** the repo.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
4. Deploy. Vercel serves over HTTPS, which the camera requires.

## Notes

- OpenCV.js, GSAP and the Manrope font load from public CDNs, so an internet connection is needed.
- Photos are saved in the browser (IndexedDB), last 20 kept.
