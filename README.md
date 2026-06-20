# Snip — Video to Ringtone (PWA)

Converts video → trimmed MP3 ringtone, entirely on your device.
Nothing uploads anywhere; FFmpeg runs locally in the browser.

## Files (all must stay in the repo ROOT, not in a subfolder)
- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png

## Deploy to GitHub Pages

1. Create a new repository (e.g. `snip-ringtone`). Public.
2. Upload all 5 files above to the **root** of the repo
   (drag them into the "Add file → Upload files" box on github.com).
3. Commit.
4. Go to **Settings → Pages**.
5. Under "Build and deployment", Source = **Deploy from a branch**.
   Branch = **main**, folder = **/ (root)**. Save.
6. Wait ~1 minute. The page shows your live URL:
   `https://<your-username>.github.io/snip-ringtone/`

## Install on the Samsung Fold

1. Open that URL in **Chrome**.
2. Menu (⋮) → **Add to Home screen** (or an "Install app" button appears in the page).
3. Launch from the home-screen icon.

## Use

1. Choose a video.
2. Scrub to the start point → "Set start = now".
3. Set length (20s is typical for a ringtone).
4. Convert to MP3 → Download.
5. Set it: Settings → Sounds and vibration → Ringtone → + → pick the MP3.

> First conversion downloads the ~25 MB audio engine once (do it on WiFi),
> then it's cached and works offline.
