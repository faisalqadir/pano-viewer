# Pano Viewer

A simple 360° panorama viewer that runs in your browser. Built on [Pannellum](https://github.com/mpetroff/pannellum) 2.5.7.

**Live site:** https://faisalqadir.github.io/pano-viewer/ (starts with 5 sample room panoramas)

## How to use it
- **Choose a photo:** click a thumbnail in the left panel, use **Prev** / **Next**, or press `[` and `]`.
- **Look around:** drag to look, scroll to zoom, or use the arrow keys. There's also a fullscreen button.
- **Add your own photos:** drop them on the window or click **Add…**. They stay on your computer and are never uploaded.

Photos should be equirectangular JPEG, PNG or WebP files (a 2:1 "world map" shape for a full 360°). Cropped panoramas display correctly if they contain GPano metadata.

## Use it offline
Download `Pano Viewer.html` and double-click it. It's one self-contained file with no sample photos, and it needs no internet or server.

## Files
- `index.html`: the live site, which preloads the photos in `photos/`
- `Pano Viewer.html`: the offline version
- `photos/`: the sample panoramas
- `PANNELLUM_LICENSE.txt`: Pannellum's MIT licence
