# Browser video frame runs

Author: ExportFrames. License: CC BY 4.0. See the LICENSE file.

## What this is

Measured extraction runs, a container decode table, and the numeric controls from one browser-only video frame extractor. The prose limits are in limits.md. Nothing here was filled in to pad the repository.

## How to use the files

Open the CSV files in a spreadsheet. Each row is one published result or one control the page already uses. The decode table records Chrome on macOS only. The page says Safari and Firefox have not been tested. ZIP size changes with the browser PNG encoder. Times vary by machine and codec.

## Where the numbers come from

Copied from the live page on 2026-10-19 (US Eastern). The page dates the three runs to Chrome on a Mac on 16 Oct 2026, and the container rows to 17 Sep 2026 using 6-second 640 × 360 clips. The same note says HEVC / H.265 also opened in Chrome on macOS on 6 Oct 2026.

The frame extractor that produced these runs is at https://exportframes.com/.

## Files

- data/measured-runs.csv — three measured runs
- data/chrome-macos-container-decode.csv — five container rows
- data/extract-controls.csv — spacing, count, format, JPG quality, and the two caps
- limits.md — the five limit sentences from the page
- provenance.json — source heading and extraction time for each file
