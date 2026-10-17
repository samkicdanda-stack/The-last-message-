# The Last Message — Reading App

A free, mobile-first Progressive Web App for **The Last Message: A Romance Thriller — Season One** by Salman Adan.

## Included
- Ten chapters extracted from the uploaded PDF manuscript
- Responsive premium dark reading UI
- Adjustable font size and light/dark reading theme
- Local reading progress and bookmarks
- PWA manifest and service worker for installability/offline caching
- Season Two "Coming Soon" section

## Publish free with GitHub Pages
1. Create/sign in to a GitHub account.
2. Create a **public** repository named `the-last-message`.
3. Upload every file in this folder to the repository root.
4. Open repository **Settings → Pages**.
5. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/(root)`, then Save.
6. Wait for the Pages URL to appear and open it over HTTPS.
7. Test on Android Chrome and iPhone Safari.

## Add to phone home screen
- Android: open the published URL in Chrome → menu (⋮) → Install app / Add to Home screen.
- iPhone: open the URL in Safari → Share → Add to Home Screen.

## Notes
- This is a web app/PWA, not yet a native Google Play or Apple App Store app.
- Reading progress and bookmarks are stored on the reader's device, not synced between devices.
- The PDF text extraction may preserve some original line breaks or page-layout artifacts. Review the chapters in the app before launch.
- The book text is included in `book.json`; you can update it by editing that file.
