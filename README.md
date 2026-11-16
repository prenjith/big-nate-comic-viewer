# Big Nate Comic Viewer

A local comic viewer for the full Big Nate archive (1991–2026).

## Features

- Browse every strip by date, with previous/next, random, first, and last controls
- Keyboard navigation (arrow keys, space) and click-to-advance
- After June 13, 2026 (the last daily strip), only Sunday strips are shown
- Uses the correct comic for each date, including early Sunday strips

## Use it

The comics are not included in this repository (they are large and copyrighted). Download the archive from the GitHub release:

https://github.com/prenjith/big-nate-comic-viewer/releases/tag/archive-v1

The archive is split into two parts because GitHub caps release assets at 2 GB. Join them first:

```
# macOS / Linux
cat BigNateArchive.zip.part1 BigNateArchive.zip.part2 > BigNateArchive.zip

# Windows
copy /b BigNateArchive.zip.part1 + BigNateArchive.zip.part2 BigNateArchive.zip
```

Then unzip and open `bignate2.html` (the same viewer as `index.html` here) inside the unzipped folder.

A Google Drive mirror is also available. Drive shows a virus-scan warning for large files; click "Download anyway":

https://drive.google.com/file/d/11CUCZ30By0NSg3Ng3wvmO2TU_c_SuYLJ/view

## Notes

- The viewer expects three sibling folders: `big_nate_comics`, `downloaded_comics`, and `newest_comics`.
- New Sunday strips are added automatically on the machine that maintains the archive, and the Drive zip is refreshed.
