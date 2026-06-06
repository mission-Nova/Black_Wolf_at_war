CA Final AIR-1 Black Wolf OS — ICON FIXED Tablet PWA Package

This package fixes tablet home-screen icon issues.

What changed:
- Added opaque black-wolf PNG icons. Transparent icons can fail or look blank on some tablet home screens.
- Added root apple-touch-icon.png for iPad/iPhone/Safari.
- Added explicit manifest and icon links using ./ paths for GitHub Pages subfolders.
- Updated cache version so browsers fetch the new manifest/icon files.

Upload structure on GitHub must be exactly:
index.html
manifest.json
sw.js
apple-touch-icon.png
favicon-192.png
favicon-512.png
icons/icon-72.png ... icon-512.png

Important reinstall steps:
1. Delete/remove the old installed home-screen app.
2. Open the GitHub Pages URL in browser.
3. Add ?v=2 to the end of the URL once, for example:
   https://USERNAME.github.io/REPO/?v=2
4. Open that URL and install/add to home screen again.
5. If the old icon still appears, clear browser site data for the GitHub Pages URL and reinstall.

For GitHub Pages, do not upload only this ZIP. Extract it and upload the files/folders.
