# CHANGELOG.md

## 1.3.0 (2025-04-16)

**Fix:**

  - [#63](https://github.com/unsplash/datasets/issues/63): Longitude and latitude no longer swapped

**New:**

  - Added `user_suggestion_source` in the `keywords` dataset
  - Added Unsplash topics in the `collections` dataset (check `collection_type`)

**Data:**

  - Added 1.4M+ photos to the dataset (submitted up to `2025-01-01`)
  - Removed unavailable photos (that are removed from the platform)
  - The `conversions` period is now from `2024-01-01` to `2025-01-01`

**Lite dataset link:**

  - Version link: [Version 1.3.0](https://unsplash.com/data/lite/1.3.0)

**Integrity checks (SHA-256):**

  - Lite: `c3c09225c4aee1c62cee1e7032db879d10b84407ed2953c2abf77dc6ca4c4ade`
  - Full: `4ad1a3cb2b38529529f92bdc9ab4237a8b9b1153f1d615ff136581297ed5b58d`

## 1.2.2 (2024-02-09)

**Data:**

  - Added 600k+ photos to the dataset (submitted up to `2024-01-01`)
  - Removed unavailable photos (that are removed from the platform)
  - The `conversions` period is now from `2023-01-01` to `2024-01-01`

**Lite dataset link:**

  - Version link: [Version 1.2.2](https://unsplash.com/data/lite/1.2.2)

**Integrity checks (SHA-256):**

  - Lite: `c187e0f24320bb32dc2acd3c387ca57c06cf5f52369816df4ab27f3cdf30e8de`
  - Full: `7783f029dc12eb54289bbb7be98acaaa585dad9ddcec44641213eed94119918c`

## 1.2.1 (2023-05-02)

**Fix:**

  - [#46](https://github.com/unsplash/datasets/issues/46): Fixed some wrong photo URLs

**Data:**

  - Added 1.5M+ photos to the dataset
  - Removed unavailable photos (that are removed from the platform)
  - The `conversions` period is now from `2022-05-01` to `2023-05-01`

**Lite dataset link:**

  - Version link: [Version 1.2.1](https://unsplash.com/data/lite/1.2.1)

**Integrity checks (SHA-256):**

  - Lite: `d29a13678f1cc3a3e706897b0a8dbbdb5837715b0d78d0492b68b9b5e96b03db`
  - Full: `3879c4f20897e564708e7da41a55f505eb6bbb13e37dbb62ae451af9782c8d87`

## 1.2.0 (2021-07-30)

**New:**

  - [#36](https://github.com/unsplash/datasets/issues/36): Included [BlurHash](https://blurha.sh/) of each photo in the dataset

**Fix:**

  - [#39](https://github.com/unsplash/datasets/issues/39): Fixed AI confidence for AI keywords

**Data:**

  - Added more search conversions
  - Historical data for search conversions will now be limited to 1 year before each version's release date.
  - Added ~1M photos to the Full Dataset.
  - Replaced 794 dead photos (removed from Unsplash) in the Lite Dataset with approved photos

**Lite dataset link:**

  - Version link: [Version 1.2.0](https://unsplash.com/data/lite/1.2.0)

**Integrity checks (SHA-256):**

  - Lite: `461fa4a1796b7966fc3aa904ce2e7f18890323243ed0e95f47c7042b335fcd98`
  - Full: `daa99dab8ba7a47d530356311ffa73f17eb403898a75399c54812e9dd582f8af`

## 1.1.0 (2020-09-23)

**New:**

  - [#10](https://github.com/unsplash/datasets/issues/10): Included user descriptions of the photos 
  - [#21](https://github.com/unsplash/datasets/issues/21): Included width, height and aspect ratio of photos
  - [#22](https://github.com/unsplash/datasets/issues/22): Included colors data from photos, coming from a 3rd party AI

**Fix:**

  - [#13](https://github.com/unsplash/datasets/issues/13): Trimmed [some fields](https://github.com/unsplash/datasets/issues/13#issuecomment-674709294).
  - [#29](https://github.com/unsplash/datasets/issues/29): Replaced newlines in keywords file by spaces to avoid CSV importation issues

**Data:**

  - Replaced 307 deleted photos in the Lite dataset with new approved photos
  - Removed about 17k deleted photos in the Full dataset
  - Updated conversions data with latest conversions. Full dataset now weighs ~25GB (vs. 16GB)

**Lite dataset link:**

  - Version link: [Version 1.1.0](https://unsplash.com/data/lite/1.1.0)

**Integrity checks (SHA-256):**

  - Lite: `266e45a8658ab2456779b3376b109e435e595646126846603f2efee5b47ee526`
  - Full: `19abc3494bda06e36e61ccabf4dd2ca8e046ac50a5e4e3570cc8aa89ed6a9713`

## 1.0.1 (2020-08-11)

**Fix:**

  - [#13](https://github.com/unsplash/datasets/issues/13): AI landmarks were always empty.
  - Some landmark names were blank instead of NULL
  - Removed duplicated photo id `zV2-QjJqkI` in the Full Dataset

**Lite dataset link:**

  - Version link: [Version 1.0.1](https://unsplash.com/data/lite/1.0.1)
  - Lite dataset links now follow the pattern `https://unsplash.com/data/lite/{version}`

**Integrity checks (SHA-256):**

  - Lite: `aa199951dd8756563f7ffef4abbc2d20c845bcff62241ae677af523728819d60`
  - Full: `ee47f7542e5ef260e6b904046b4837532f420412a0e2c299dcecab55acd28d1f`
