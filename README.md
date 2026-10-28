# Pain Free Posture Routine

Mobile-friendly Progressive Web App for the Egoscue **TMJ & Neck/Head** E-cise menu. Browse the sequence, run a guided session with timers and set tracking, and log completed workouts on-device.

## Features

- Installable PWA (Add to Home Screen on iOS and Android)
- Guided workout mode with hold timers and set check-offs
- Exercise detail cards with posture diagrams
- Session history stored in `localStorage`
- Offline support via service worker
- Light / dark theme toggle

## Run locally

PWAs need a local server (not `file://`):

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## Publish to GitHub Pages

1. Create a GitHub repository and push this folder.
2. In the repo: **Settings → Pages → Build and deployment**.
3. Set **Source** to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. After it deploys, open `https://<you>.github.io/<repo>/` on your phone and use **Install** / **Add to Home Screen**.

GitHub Pages is HTTPS, which is required for installability and the service worker.

## Install on a phone

- **iPhone:** Safari → Share → Add to Home Screen  
- **Android:** Chrome → Install / Add to Home Screen (or the in-app **Install** button)

## Disclaimer

This app is a personal practice menu derived from published Egoscue E-cise descriptions. It is not medical advice. Stop if you feel pain and consult a qualified clinician.
