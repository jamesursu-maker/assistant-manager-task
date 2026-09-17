Assistant Manager – Project Task Manager
NEW MOBILE PWA BUILD

Base: Desktop Final / Work History Final
PWA rebuild date: 17-09-2026

This package intentionally starts a fresh PWA layer. Previous PWA manifest/service-worker settings are not reused.

Files:
- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png

Hosting:
Serve the folder over HTTPS. For GitHub Pages, keep index.html at the published root.

Note:
The application data logic and Work History are carried from the Desktop Final base. The new PWA layer only adds fresh install metadata/service-worker support and responsive presentation.
