# encore — landing page

Static Vite site. Three pages: `index.html`, `privacy.html`, `terms.html`.

## Deploy to Vercel

1. Push the **contents of this folder** to your repo root — `package.json` must sit at the top level, not inside a subfolder.
2. In Vercel, import the repo. Framework Preset: **Vite**. Root Directory: `./`.
3. Build command `npm run build`, output directory `dist` (both preset by `vercel.json`).

## Local

```
npm install
npm run dev
```

## Structure

- `index.html` — landing page
- `privacy.html` / `terms.html` — legal pages, declared as build inputs in `vite.config.js`
- `public/` — served at the domain root: `support.js` (render runtime), `encore-logo.png`, `favicon.svg`
