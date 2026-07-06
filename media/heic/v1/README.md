# HEIC Fixtures (v1)

Fixtures for HEIC decoding and media metadata tests.

## Contents

- `files/1718_rotate_90_cw.HEIC`: HEIC with a rotate-90 orientation case.
- `files/7765_horizontal_normal.HEIC`: HEIC with a normal orientation case.
- `files/7949_mirror_horizontal_rotate_270_cw.HEIC`: HEIC mirrored and rotated
  270 degrees clockwise.
- `files/IMG_0682_pano.HEIC`: HEIC panorama image.
- `files/IMG_0983.HEIC`: HEIC rotate-90 low-light photo taken on an
  iPhone 17 Pro. It can produce artefacts on some decoders, so it is included
  to test decoder robustness around auxiliary image references.
- `files/IMG_8606_rotate_90_cw_contains_text.HEIC`: HEIC rotate-90 image with
  visible text and auxiliary image references.
- `manifest.json`: Canonical metadata copied from the ML indexing fixture
  manifest for HEIC-specific validation.

## Provenance

Copied from `ml/indexing/v1/files` to provide a dedicated HEIC-only media test
set while preserving the original ML indexing fixtures.
