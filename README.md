# foto-org

A Windows application for scanning, de-duplicating, and organising your
photo library into a clean, date-ordered archive — without ever changing
or deleting your original photos.

## Features

- Scan a folder (and optionally all subfolders) for photos, exact
  duplicates, and visually similar images
- Group duplicate and near-identical photos together using exact and
  perceptual matching
- Automatically identify the best-quality or most original photo in each
  duplicate group
- Flag low-detail, blurry, poorly exposed, tilted, and document photos
  for review
- Choose exactly which photos to keep in each group (multiple keepers
  allowed) — nothing is ever deleted, only included or excluded from the copy
- Remove individual photos, or an entire group, from a duplicate group
  (they are then treated as unique)
- Clear the low-detail flag on photos to keep them
- Build an organised **archive**: copy the photos you keep into one of
  three folder structures — single folder, numerical date (2024\01\15),
  or readable date (2024\01 - January\15)
- Add to an existing archive incrementally: the destination's structure
  is detected automatically, and photos already present are skipped so
  only new photos are copied
- Adjustable scan accuracy and detection settings
- Runs entirely offline — no photo or personal data ever leaves your device

## Roadmap

- [x] Scan for duplicate photos
- [x] Show groups of duplicates
- [x] Identify the best photo of duplicates
- [x] Identify low-information photos
- [x] Identify out-of-focus photos
- [x] Allow photos to be removed from duplicate / flagged groups
- [x] Settings to control scanning and file-handling behaviour
- [x] Copy kept photos into a new folder with a date hierarchy
- [x] Detect an existing archive's structure and add only new photos to it
- [ ] Optional content-based (hash) matching when adding to an archive
- [ ] Support additional archive folder structures

## License

MIT
