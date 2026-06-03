# 📺 Video Proxy Player

iFrame URL পেস্ট করো, সাথে সাথে video play হবে।

## Features
- iframe `src` URL বা full `<iframe>` tag — দুটোই সাপোর্ট করে
- History সেভ হয় (localStorage)
- **PWA** — Add to Home Screen করলে app-এর মতো কাজ করে
- Offline support (service worker)

## GitHub Pages Deploy

1. এই repo fork বা clone করো
2. **Settings → Pages → Source:** `GitHub Actions` সিলেক্ট করো
3. `main` branch-এ push করো → auto deploy হবে

## Local Run

```bash
# যেকোনো static server দিয়ে চালাও
npx serve .
# অথবা
python3 -m http.server 8080
```

> ⚠️ Service worker HTTPS বা localhost ছাড়া কাজ করে না।
