# EDB Foundation Website

A static, single-page website for Everyone Deserves Better Foundation.

## Deploy on Vercel

1. Sign in to Vercel and click "New Project".
2. Import this repository.
3. Framework preset: "Other" (static site).
4. Root directory: project root (where `index.html` is).
5. No build command required. Output directory: not needed.
6. Deploy.

Vercel will serve `index.html` at the root. The provided `vercel.json` marks this as a static site.

## Assets

- Place your logo at the project root as `edb-logo.png` (or update `<img src>` in `index.html`).
- Add gallery images under `images/` and update the `src` paths if names differ.

## Local Development

Just open `index.html` in your browser, or serve locally with a simple static server:

```bash
npx serve .
```

## Contact Links

`index.html` includes Email, Phone/WhatsApp, Instagram, Facebook, and TikTok links in the Contact section.
