# Dr. Muhammad Arif — Orthopedic Surgeon, Sialkot

Single-page website for Dr. Muhammad Arif. Plain HTML, no build step.

## Files
- `index.html` — the whole website (styles, scripts and images are inside this file)
- `robots.txt` and `sitemap.xml` — for Google indexing
- `og-image.jpg` — preview picture shown when the link is shared
- `favicon.ico`, `favicon-*.png`, `apple-touch-icon.png`, `site.webmanifest` — the doctor's photo as the browser tab / Google icon
- `vercel.json` — small caching/security headers for Vercel

## Things to edit (all inside `index.html`)
- WhatsApp / call number: search for `var PHONE=` near the bottom
- Clinic timings and booking slots: search for `slots()`
- Map location: search for `maps.google.com/maps?q=`
- Page title and description: top of the file in `<head>`

## Deploy on Vercel
1. Push this folder to a GitHub repository.
2. On vercel.com choose **Add New → Project** and import the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty. Click **Deploy**.
4. Add your own domain under **Project → Settings → Domains**.

After the domain is ready, add `<link rel="canonical" href="https://YOUR-DOMAIN/">` inside `<head>` and submit the site in Google Search Console.
