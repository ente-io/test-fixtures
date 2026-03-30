# Motion Photo Fixtures (v1)

Fixtures for motion photo detection and extraction tests.

## Contents

- `files/motionphoto.jpg`: Expected motion photo.
- `files/motionphoto.heic`: Expected motion photo.
- `files/pixel_6_small_video.jpg`: Expected motion photo (Top Shot variant).
- `files/pixel_8.jpg`: Expected non-motion photo.
- `files/normalphoto.jpg`: Expected non-motion photo.
- `files/dual_mp4_video_first.jpg`: Expected motion photo (dual-MP4, larger video first).
- `files/dual_mp4_video_last.jpg`: Expected motion photo (dual-MP4, larger video last).
- `manifest.json`: Canonical expected metadata and outputs.

## Provenance

Most fixtures were copied from `ente-io/motion_photos` test assets to centralize fixture reuse across Ente apps.

`dual_mp4_video_first.jpg` is a sanitized sample added to cover dual-MP4 ordering where the larger embedded video precedes the smaller preview clip.
