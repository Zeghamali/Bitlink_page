# Bitlink Static Site (Vercel-Ready)

This folder is ready to deploy to **Vercel** with a free `.vercel.app` domain.

## Deploy via GitHub (auto-deploys)

1. Push these files to a GitHub repo (root must contain `index.html`).
2. Go to https://vercel.com → **Add New → Project** → **Import Git Repository**.
3. Framework Preset: **Other**.
4. **Build Command**: _leave empty_ (static site).
5. **Output Directory**: _leave empty_ (files are at repo root).
6. Click **Deploy** → you’ll get `your-project.vercel.app`.

## Deploy via Vercel CLI (no Git)

```bash
npm i -g vercel
vercel    # answer prompts: Framework: Other, Output: .
vercel --prod
```

You’ll get a live **.vercel.app** URL immediately.
