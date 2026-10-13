# Happy Birthday 💖

A birthday website. Open `index.html` in a browser to preview it.

## Personalize it
1. Open `index.html` and edit the `CONFIG` block near the bottom (name, letter, captions, reasons).
2. Put photos in `assets/images/` and videos in `assets/videos/`, then list them in `CONFIG.memories` (file name + caption).
   Keep each video under 50 MB. GitHub won't accept a file over 100 MB.
3. Optional: add a song (e.g. `music.mp3`) to this folder and set `music: "music.mp3"`.

## Put it on GitHub Pages
1. Create a new repository on https://github.com/new (e.g. `happy-birthday`), Public.
2. In this folder run:
   ```bash
   git init
   git add .
   git commit -m "Birthday site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/happy-birthday.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
4. After about a minute, the site is live at `https://<your-username>.github.io/happy-birthday/`.
