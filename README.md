# AI Coworker Essential — Full-View Poster

A single-page, static site that displays the Siametrics poster full-view. Responsive (scales to fit any screen), click-to-zoom to 1:1, ready for Vercel.

## 1. Add the image

Save the poster image into this folder as:

```
poster.png
```

(That's the filename `index.html` references. Keep it `.png`, or update the `src`/`og:image` paths if you use another extension.)

## 2. Deploy to Vercel

No build step — it's pure static.

**Option A — CLI**
```bash
npm i -g vercel
vercel        # preview
vercel --prod # production
```

**Option B — Git**
Push this folder to a GitHub repo and "Import Project" in Vercel. Framework preset: **Other**. Output dir: root. No build command.

## Files
- `index.html` — the full-view page (responsive, click-to-zoom, OG tags)
- `poster.png` — your poster image (you add this)
- `vercel.json` — clean URLs + long-cache header for the image
# prad-pmat-ai-cowork-essential
