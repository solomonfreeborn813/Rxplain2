# Rxplain

A drug information landing page with live search. Type a brand or generic name and get the official FDA label sorted into Uses, Dosage, Warnings, Side effects, Interactions, Special groups, Storage and Overdose. Includes a glassmorphism design with light and dark mode, and optional AI plain-language summaries.

**Live:** https://rxplain2.vercel.app

## Data sources (free, no API key)
- [openFDA drug label API](https://open.fda.gov/apis/drug/label/) for label text
- [NIH RxNorm API](https://lhncbc.nlm.nih.gov/RxNav/APIs/RxNormAPIs.html) for spelling suggestions
- [Pollinations text API](https://text.pollinations.ai) for the optional AI summary. It only rewrites the label text already on screen, and the original text always stays visible.

## Files
- `index.html`: the whole site (HTML, CSS and JS in one file, no build step)
- `site.webmanifest`, `browserconfig.xml`: install and tile settings
- App icons, all in the repo root: `favicon.ico`, `favicon-16x16.png`, `favicon-32x32.png`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-192.png`, `icon-maskable-512.png`, `mstile-70x70.png`, `mstile-150x150.png`, `mstile-310x310.png`

## Run it
Open `index.html` in a browser. No build step.

## Host it free
- **GitHub Pages:** repo Settings > Pages > Deploy from a branch > `main` / root.
- **Vercel or Netlify:** import this repo. Framework preset: Other. No build command, no output directory.

## Disclaimer
Information only. Not medical advice. AI summaries can contain mistakes, so always read the original label text.
