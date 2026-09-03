# ML OCR Fixtures (v1)

Fixtures for cross-platform OCR regression and integration tests.

## Contents

- `files/bob_ios_detection_issue.JPEG`: WhatsApp voucher screenshot that
  previously lost detections on iOS.
- `files/heic_test.HEIC`: HEIC photo of an HDFC UPI payment sign.
- `files/meme_ice_cream.jpeg`: English ice-cream meme.
- `files/meme_love_you.jpeg`: English Pokemon meme.
- `files/meme_perfect_couple.jpeg`: English temperature-compatibility meme.
- `files/meme_waking_up.jpeg`: English waking-up meme.
- `files/ocr_not_working.jpg`: Hungarian business-card regression case.
- `files/ocr_test.jpeg`: Vietnamese restaurant receipt.
- `files/ocr_working.jpg`: Electric-meter regression case.
- `files/receipt_swiggy.jpg`: English food-delivery receipt.
- `files/screen_photos.jpeg`: Dutch government FAQ screenshot.
- `files/text_photos.jpeg`: Dutch poetry photographed on a sign.
- `ground_truth.json`: Human transcriptions and stable OCR assertions.
- `manifest.json`: Canonical file hashes, sizes, MIME types, and coverage tags.

## Expectations

OCR engines and platform releases do not produce identical line segmentation or
transcriptions. In `ground_truth.json`, `texts` is a human-readable reference;
the executable contract is the looser combination of:

- `requiredTexts`: stable semantic anchors expected on every platform.
- `iosRequiredTexts` and `androidRequiredTexts`: optional engine-specific
  anchors.
- `minimumBlocks`: the minimum number of detected text blocks.

Consumers should normalize case and punctuation when matching required text.

## Provenance

Copied from the `mobile_ocr` example fixture suite at commit
`0c68f88f20607cfcb10286422860350ccb024acd`. The image files are copied
byte-for-byte so their hashes remain comparable with the source suite; the
human transcriptions were visually reviewed for this dataset.
