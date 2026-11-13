# Fifths — Key Signature Trainer

A mobile-first, offline-capable trainer for all 15 major and 15 minor key signatures, with spaced repetition.

**GitHub Pages site:** https://jukkalaurila.github.io/fifths-key-signature-trainer/

## Features

- Identify keys from notation, choose written signatures, and recognize relative major/minor keys.
- Adaptive practice with a separate learning history for each major and minor key.
- Again / Hard / Good / Easy ratings and spaced review intervals.
- Learning progress, daily new-key settings, and JSON backup import/export.
- Offline-capable installable web app; no backend, analytics, or external dependencies.

## Enable GitHub Pages

1. Under **Settings → Pages**, select **GitHub Actions** as the source.
2. The workflow at `.github/workflows/deploy.yml` automatically deploys on pushes to `main`.
3. Open https://jukkalaurila.github.io/fifths-key-signature-trainer/ after the deployment completes.
4. To install on an iPhone, open the URL in Safari and choose **Share → Add to Home Screen**.

## Privacy and backups

Progress is stored in the browser's localStorage for this site. It is not synced between devices. Use the app's export/import function to back up progress or move it to another device.

## Code

The trainer is dependency-free, with its JavaScript and CSS in `index.html`. `manifest.webmanifest` provides install metadata, `sw.js` enables offline caching, and `.github/workflows/deploy.yml` publishes the site.
