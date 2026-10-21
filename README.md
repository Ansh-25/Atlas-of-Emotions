# Emotional Atlas

An interactive, mobile-friendly emotional vocabulary explorer. It runs as a static site and can be installed as a Progressive Web App (PWA).

## Publish with GitHub Pages

1. Create a GitHub repository named `emotional-atlas`.
2. Upload **all files and folders in this project** to the repository root. `index.html` must be at the root, not inside another nested folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the Pages deployment to finish. Your site URL will usually be `https://YOUR-USERNAME.github.io/emotional-atlas/`.

## Install it like an app

- **Android (Chrome):** open the published HTTPS site, then use the browser menu → **Install app** or **Add to Home screen**.
- **Desktop (Chrome/Edge):** open the site and use the install icon in the address bar, or the browser menu → **Install Emotional Atlas**.
- **iPhone/iPad (Safari):** open the site, tap **Share**, then **Add to Home Screen**.

The manifest supplies the app name, theme and icon. The service worker caches the app files after a successful first load to provide basic offline reopening. Updates may take a reload or two to replace cached files; the service-worker cache version can be incremented in `service-worker.js` when publishing a new release.

## Files

- `index.html` — application and interface
- `manifest.json` — PWA install metadata
- `service-worker.js` — offline cache
- `icons/` — install and browser icons

## License

MIT. See `LICENSE`.
