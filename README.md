# Big Nate Comic Viewer

A local comic viewer for the full Big Nate archive (1991–2026).

## Features

- Browse every strip by date, with previous/next, random, first, and last controls
- Keyboard navigation (arrow keys, space) and click-to-advance
- After June 13, 2026 (the last daily strip), only Sunday strips are shown
- Uses the correct comic for each date, including early Sunday strips

## Use it

The comics are not included in this repository (they are large and copyrighted). Download the full archive zip from Google Drive:

https://drive.google.com/open?id=1cu14xl9gws3DBUZSivmbr3_cGv0rVjd_

Unzip it, then open `bignate2.html` (the same viewer as `index.html` here) inside the unzipped folder.

## Notes

- The viewer expects three sibling folders: `big_nate_comics`, `downloaded_comics`, and `newest_comics`.
- New Sunday strips are added automatically on the machine that maintains the archive, and the Drive zip is refreshed.
