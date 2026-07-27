# عيادات الجبيهة الطبية · Jubaiha Medical Clinics

A professional, modern, **bilingual (Arabic / English)** informational website for
Jubaiha Medical Clinics — a 24-hour emergency & walk-in clinic in Al-Jubeiha, Amman.
It features one-tap **WhatsApp appointment booking** and click-to-call.

## ✨ Features

- **Bilingual with instant AR ⇄ EN toggle** — full RTL/LTR support, remembers the visitor's choice.
- **WhatsApp booking** — every "Book" button opens WhatsApp with a ready-made message (in the visitor's language) to **+962 7 9576 2673**.
- **Click-to-call** — phone numbers open the dialer on mobile.
- **Professional type** — IBM Plex Sans Arabic + Plus Jakarta Sans.
- **Modern responsive design** — hero, services, about, booking CTA, contact + live map, footer, and a floating WhatsApp button.
- **Fast & dependency-free** — a single `index.html` plus the logo. No build step.

## 📁 Structure

```
index.html          → the whole website
assets/logo.webp    → clinic logo (WebP, optimized)
assets/logo.jpg     → logo fallback
```

## 🚀 Free hosting (no GitHub required)

The site is plain static files, so it deploys anywhere. Two recommended free hosts:

### Vercel (via CLI — no Git needed)
1. Install Node.js (LTS) from <https://nodejs.org> if you don't have it.
2. Open a terminal in this folder and run:
   ```bash
   npm i -g vercel
   vercel login      # choose "Continue with Email"
   vercel --prod     # press Enter through the prompts
   ```
3. It prints your live URL, e.g. `https://jubaiha-clinic.vercel.app`.
4. Rename it or add a custom domain under **vercel.com → Project → Settings → Domains**.

### Netlify Drop (click-only, no terminal)
1. Go to <https://app.netlify.com/drop>.
2. Drag this folder (or the zip) onto the page — it's instantly live.
3. Sign up (free) to keep it and rename it to `jubaiha-clinic.netlify.app`.

> **Cloudflare Pages** works too: create a free account and upload the folder — you get a fast `*.pages.dev` URL with free HTTPS and custom domains.

## ✏️ Updating clinic info

Everything lives in `index.html`:

- **WhatsApp number** — edit `var WA_NUMBER = "962795762673";` in the `<script>` at the bottom.
- **Pre-filled booking message** — edit the `MSG` object (Arabic + English) in the same script.
- **Phone / email / Instagram / address** — search the Contact and Footer sections.
- **Text** — each language has `.ar` / `.en` elements; edit both to keep them in sync.

## 📞 Clinic details

| | |
|---|---|
| Phone / WhatsApp | +962 7 9576 2673 |
| Email | bkh08706@gmail.com |
| Instagram | [@clinics_emergency](https://www.instagram.com/clinics_emergency) |
| Address | Rest Hills Hotel, Yajouz Rd, Al-Jubeiha, Amman — Floor 1, Office 3 |
| Hours | Open 24 hours, every day |
