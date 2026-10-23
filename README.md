# CineForge AI — GitHub Pages Starter

A responsive, dark cinematic **front-end prototype** for an image-to-video AI studio.

## What works
- Image upload with local preview (file stays in your browser)
- Drag-and-drop image selection
- Motion prompt, duration, aspect ratio, motion intensity and camera controls
- Basic input validation and generation-settings summary
- Responsive layout for phones and desktop

## Important limitation
This is a user-interface prototype. It does **not** generate actual videos. Real generation needs a video-generation provider/API and a secure backend. Do not put API keys in `index.html` or any public GitHub repository.

## Publish with GitHub Pages
1. Sign in to GitHub and create a **new public repository** named `cineforge-ai` (or any name you like).
2. Add/upload `index.html` and this `README.md` to the repository's root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then press **Save**.
6. Wait a minute or two and refresh the Pages section; GitHub will show the website URL.

If you use a repository named `YOUR-USERNAME.github.io`, the site URL is usually `https://YOUR-USERNAME.github.io/`. For other repository names, it is usually `https://YOUR-USERNAME.github.io/cineforge-ai/`.

## Next step for real AI video generation
Choose a video-generation provider, check its current API access/pricing/terms, and build a backend endpoint that receives the image and settings, calls the provider with a secret API key, then returns a job status and video URL. Keep all provider secrets server-side.
