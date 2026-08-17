# Michael ♥ Donnah — Monthsary Love Website

A romantic static website built with HTML, CSS and JavaScript.

## Included

- Philippines time (Asia/Manila)
- Monthsary timeline and date locks
- Monthly love letters
- SpeechSynthesis reading controls
- Donnah reply system
- Love messages and 100 reasons
- Open-When letters
- 3D memory universe
- Existing photo memories
- Mobile-first responsive layout
- **Private Couple Photo Vault**
- Separate **Our Memories / Michael / Donnah** albums
- Multi-photo uploads
- Local IndexedDB fallback
- Optional Firebase Auth + Firestore + Storage for private cross-device photo sync

## Important privacy note

A GitHub Pages static site cannot securely synchronize private photos by itself. The new Private Couple Photo Vault therefore has two modes:

- **Local mode:** immediate, browser-only storage on the current device.
- **Firebase mode:** authenticated, cross-device shared storage protected by Firebase Security Rules.

See `FIREBASE_SETUP.md` for the exact setup.

## Files

- `index.html`
- `style.css`
- `script.js`
- `firebase-config.js`
- `firestore.rules`
- `storage.rules`
- `FIREBASE_SETUP.md`
- `PHOTO_FILES.txt`

## Existing image assets

Keep the existing photo files from the original project in the repository. The project already references those images in `script.js`.
