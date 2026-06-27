# White Glass Chess ♔

A fast, offline-ready chess game with a clean white glass UI. Built to run in the browser and package as a PWA/Android app.

## **Features**
- **2-Player Local Mode**: Play on the same device, no login needed
- **PWA Support**: Install to home screen on Android/Desktop 
- **Responsive Glass UI**: Clean, minimal white glass design
- **Standard Chess Rules**: Castling, en passant, promotion included
- **Offline Play**: Works without internet after first load

## **Tech Stack**
- **Frontend**: HTML, CSS, Vanilla JavaScript 
- **PWA**: `manifest.json` + `service-worker.js` for offline install
- **No Backend Required**: 100% client-side

## **How to Run Locally**
1. Download/unzip the project
2. Open `index.html` in your browser 
   Or use a local server: `python -m http.server` then go to `http://localhost:8000`

## **How to Install as an App**
1. Open the game URL in Chrome/Edge on Android
2. Tap `Install app` / `Add to Home Screen` 
3. Play offline from your home screen

To build a standalone `.apk`: Upload this repo URL to [PWABuilder](https://www.pwabuilder.com) → Export Android.

## **File Structure**
