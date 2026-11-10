# 11:11 — A Forever Promise (Afreen)

A responsive, single-page birthday experience built with HTML, CSS and vanilla JavaScript.

## Run locally
Open `index.html` in a modern browser. For camera recording, run from localhost or HTTPS because browsers restrict camera access on insecure origins.

Recommended local server:
- Python: `python3 -m http.server 8000`
- Open: `http://localhost:8000`

## Personalise before presenting
1. Replace the four timeline milestone headings and descriptions in `index.html` with your actual dates and memories.
2. Edit the letter so it sounds like you. Add your own signature.
3. Add your own specific reasons in the `reasons` array in the script.
4. Upload your photographs/videos in the Memories section during the presentation.
5. Record or upload your personal birthday video in the video section.

## Important storage note
The photo/video selections are held as browser object URLs in the current page session. They are not uploaded to a server and will not persist after refreshing or closing the page. Keep original media files separately. For a permanent hosted version, add a private storage backend and authentication.

## Music
The Sound button creates a simple original ambient instrumental using the browser's Web Audio API. It requires a user click and does not use a copyrighted recording.

## Hosting
Upload the contents of this folder to any static hosting provider that serves HTML files over HTTPS. HTTPS is required for camera recording on deployed sites.
