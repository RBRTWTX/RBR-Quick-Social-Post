# RBR Quick Social Post (v1)

A static, no-backend, touch-first 1080 × 1080 weather graphic editor. Works on GitHub Pages and can be added to the iPhone Home Screen as a web app.

## Upload to GitHub Pages

1. Unzip this package. Upload **the files and `icons` folder inside** `rbr-quick-social-post` to the **root** of a GitHub repository. Do not upload the ZIP itself as a single file.
2. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
3. Wait for the GitHub Pages deployment. Open the published HTTPS URL on iPhone in **Safari**.
4. Tap **Share → Add to Home Screen**, enable **Open as Web App** if offered, then **Add**.

## Use

- Tap blue header to edit title/subtitle.
- Tap the white area to upload an image; drag to reposition; pinch to zoom; tap again for zoom slider.
- Tap each of the three dark panels to edit its text.
- Tap each of the 12 small indicator rectangles to choose an NWS/SPC-style color.
- Tap the long dark lower bar or gray footer to edit.
- Tap **✱** for Download PNG, Share PNG, Undo, Redo, Save/Open Project, layouts, and New.
- Export is always a square 1080 × 1080 PNG. Posting is manual.

## Important

- The editor itself works without a server. GitHub Pages provides the HTTPS URL required for reliable iPhone Home Screen installation.
- After the first online visit, the service worker caches app files for offline use. Open the app online once before relying on offline access.
- Editable projects are saved as downloadable JSON files, including uploaded image data. Keep these backups; browser storage can be cleared.
- No data or images are uploaded to a server by this app.
- Some iOS versions may show **Add to Home Screen** without an explicit **Open as Web App** toggle.
- On-screen menus may internally scroll if needed, but the main page never scrolls.
- The layout is a clean functional starting design, not a pixel-exact recreation of third-party branded graphics.
