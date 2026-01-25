# Deploying this site (GitHub Pages)

1. Create a GitHub repository and push this folder's contents to the repository's `main` (or `master`) branch.
2. In the repository settings -> Pages, set the source to `main` branch and root (`/`).
3. Save; the site will publish at `https://<your-username>.github.io/<repo>` shortly.

Quick local preview:

Windows (PowerShell):
```
cd path\to\forever.github.io
python -m http.server 8000
# then open http://localhost:8000 in your phone or browser
```

Notes:
- Replace the placeholder video in `index.html` with your own MP4 when ready.
- Mobile: modern phones require a user gesture to start unmuted playback; tap the play button.
