# Portfolio Website

A simple one-page portfolio template (HTML/CSS/JS, no build tools required).

## Customize

1. **Name & links** — In `index.html`, replace:
   - `Your Name` (title, hero, footer, logo)
   - `yourusername` GitHub links
   - `@yourchannel` YouTube links
   - `yourusername` LinkedIn link
   - `you@example.com` email
2. **Resume** — Add your resume PDF as `assets/resume.pdf`.
3. **Photo** — Add a headshot as `assets/profile.jpg` (optional; a placeholder box shows if missing).
4. **Projects** — Edit the three `.project-card` blocks under `#projects` with your real repos, descriptions, and tech tags. Add more cards by copying the `<article class="project-card">` block.
5. **Videos** — Replace `VIDEO_ID_ONE/TWO/THREE` in the `<iframe>` `src` attributes with your actual YouTube video IDs (the part after `watch?v=` in a YouTube URL).
6. **Certifications** — Edit `.cert-card` entries under `#certifications`.
7. **Colors** — Adjust the `:root` variables at the top of `css/style.css` (`--accent` is AWS orange by default).

## Run locally

Just open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploy

Good free/cheap options for a static site like this, especially given your AWS focus:
- **AWS S3 + CloudFront** (great portfolio piece in itself — deploying your own site on AWS)
- **AWS Amplify Hosting**
- **GitHub Pages**
