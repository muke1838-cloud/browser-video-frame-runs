# Limits chosen on this page

The frame extractor states these limits itself. They are choices on that page, not a browser specification.

- One video at a time.
- Files up to 2 GB. The video is played from your disk, not loaded into memory; the stills you extract are what use memory.
- Up to 300 frames per run. Narrow the range or space frames further to stay under it.
- Stills are the full decoded resolution of the video.
- Frame rate and frame count appear only when the file's metadata has them. Otherwise the page says so instead of guessing 30 fps.

The page script stores the file cap as the expression 2 * 1024 ** 3 bytes and the frame cap as 300. Spacing, frame-count choices, image format, and JPG quality are listed in data/extract-controls.csv.
