# TNB MEDIA — Sheikh Jikrullah (single-page landing site)

Everything (HTML, CSS, JavaScript, links, videos, pricing, text) is in ONE file: `index.html`.
No build step, no installs.

## Folder
- `index.html`        the whole website — open the top of the file for the EDIT MAP
- `assets/images/`    put `sheikh-editing-room-camera-final.webp` here (About photo)
- `.vscode/`          makes VS Code suggest the Live Server extension

## Edit in Visual Studio Code
1. File -> Open Folder -> choose this folder.
2. Install "Live Server" when suggested.
3. Right-click `index.html` -> "Open with Live Server". The page refreshes on save.
   (Don't just double-click index.html: YouTube often blocks video previews on file:// pages.)
4. Press Ctrl+F and search `[EDIT:` to jump between editable parts:
   SEO, COLORS, NAV, HERO, MARQUEE, WORK, SERVICES, PRICING, SKILLS, ABOUT, CONTACT, FOOTER, LINKS, VIDEOS.

## Links and videos
Search `[EDIT:LINKS]` (WhatsApp, email, YouTube, Instagram) and `[EDIT:VIDEOS]` (every video).
Each video has `youtubeUrl` (opened by "Watch on YouTube") and an optional `previewUrl` (direct .mp4 silent loop).
If a video shows "unavailable": YouTube Studio -> Content -> the video -> Show more -> tick "Allow embedding".

## Publish on GitHub Pages
Upload everything in this folder (keep the structure) to a GitHub repo.
Settings -> Pages -> Deploy from a branch -> `main` -> `/ (root)`.
