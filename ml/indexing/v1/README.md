# ML Indexing Fixtures (v1)

Fixtures for ML image indexing coverage tests.

## Contents

- `files/1343_rotate_90_cw.jpg`: JPEG with a rotate-90 orientation case (issue on dart.ui)
- `files/1718_rotate_90_cw.HEIC`: HEIC with a rotate-90 orientation case.
- `files/7765_horizontal_normal.HEIC`: HEIC with a normal orientation case.
- `files/7949_mirror_horizontal_rotate_270_cw.HEIC`: HEIC mirrored and rotated
  270 degrees clockwise.
- `files/IMG_0682_pano.HEIC`: HEIC panorama image.
- `files/IMG_8606_rotate_90_cw_contains_text.HEIC`: HEIC rotate-90 image with
  visible text.
- `files/IMG_8905.CR2`: Canon RAW (CR2) image.
- `files/IMG_pano.jpg`: JPEG panorama image.
- `files/astronaut.png`: PNG image.
- `files/man.jpeg`: Small JPEG portrait image.
- `files/people.jpeg`: Small JPEG image with multiple people.
- `files/singapore.jpg`: JPEG cityscape image.
- `files/starwatchers.jpg`: JPEG low-light/night scene.
- `files/ui_app.webp`: WEBP UI screenshot-style image.
- `manifest.json`: Canonical metadata (hashes, sizes, MIME types) and coverage
  tags for fixture validation.

## Provenance

Curated locally for indexing pipeline coverage across formats, orientation
variants, panoramas, text-containing images, low-light scenes, and RAW input.
