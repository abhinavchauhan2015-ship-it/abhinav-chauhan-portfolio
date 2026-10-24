# Abhinav Chauhan — Personal Portfolio

Job-hunt portfolio for Abhinav Chauhan (Principal SDET / Quality Engineering Leader).

## Stack

- Vite + vanilla HTML / CSS / JS
- Google Fonts: Unbounded, Syne, IBM Plex Mono
- Netlify-ready (`netlify.toml`, `public/_redirects`)

## Local

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm run preview
```

## Deploy to Netlify

1. Push this folder to a GitHub repo (or use Netlify CLI / drag-and-drop).
2. In Netlify: **Add new site → Import from Git** (or **Deploy manually**).
3. Build settings (also in `netlify.toml`):
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
4. Deploy. Point a custom domain when ready.

### Manual drag-and-drop

```bash
npm run build
```

Zip the `dist/` folder and drop it on [app.netlify.com/drop](https://app.netlify.com/drop).

## Content source

Copy and roles are taken from Abhinav’s resume. No invented employers or metrics.
