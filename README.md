# 📺 Video Proxy Player

🔗 **Live Site:** [https://pabitra-senpai.github.io/video-proxy-player/](https://pabitra-senpai.github.io/video-proxy-player/)

Paste any iframe URL and play the video instantly.

## Features
- Supports both iframe `src` URL and full `<iframe>` tag
- History saved automatically (localStorage)
- **PWA** — Works like an app when added to Home Screen
- Offline support (service worker)

## GitHub Pages Deploy

1. Fork or clone this repo
2. **Settings → Pages → Source:** select `GitHub Actions`
3. Push to `main` branch → auto deploy

## Local Run

```bash
# Run with any static server
npx serve .
# or
python3 -m http.server 8080
```

> ⚠️ Service worker only works on HTTPS or localhost.
