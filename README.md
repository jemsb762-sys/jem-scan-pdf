# Jem Scan PDF — Offline Edition

No external JavaScript libraries, API keys, backend, database account, remote fonts, or runtime CDN requests.

Features: camera capture (HTTPS permission required), import photos, crop by percentage edges, rotate, Original/Document/Grayscale/B&W filters, multi-page PDF creation, A4/Letter/Fit page sizes, IndexedDB device storage, download/delete, installable PWA and service-worker cache.

Limitations: Existing PDF files cannot be imported or merged in this fully offline edition. Import image files or scan paper pages instead. Cropping is manual, not automatic edge detection. First open the deployed HTTPS app while online so the service worker can cache the app shell. Thereafter scanning, photo import, editing and PDF creation work offline. PDFs stay in this browser on this device; download backups before clearing browser data.

Deploy: upload all files/folders to GitHub. Import in Vercel; Framework Preset Other, Build Command blank, Output Directory `.`, Install Command blank. Use HTTPS.

iPhone: open in Safari → Share → Add to Home Screen. Android: open in Chrome → Install app.
