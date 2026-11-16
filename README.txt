# HABI App (PWA)

## Files
- `index.html` — HABI app interface
- `manifest.json` — installable app metadata
- `service-worker.js` — app-shell/offline caching
- `icons/` — HABI app icons

## Publish
Upload the contents of this folder to the root of a GitHub Pages repository (keep the `icons` folder). Ensure GitHub Pages is enabled and use the HTTPS Pages URL.

## Install
- Android / Chrome: open the HTTPS site and choose Install app / Add to Home screen.
- iPhone / iPad: open the HTTPS site in Safari → Share → Add to Home Screen.
- Windows / supported desktop browsers: use the install icon in the address bar or browser menu.
- Other devices can use the HTTPS website in a modern browser.

## Important current limitations
This is an installable PWA wrapper around the supplied prototype. Existing module data uses browser/device local storage in multiple places, so submissions and account/demo state are not automatically shared between different devices or users. A real shared deployment needs a secure backend/database, real authentication and role permissions, and configured API integrations. Offline mode caches the app shell; live maps, external links, AI services, and other online data still need internet. Do not treat demo emergency alerts, dashboard sample statistics, or demo login as a live public-safety service.
