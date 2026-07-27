# عيادات الجبيهة الطبية · Jubaiha Medical Clinics

A professional, modern, **bilingual (Arabic / English)** informational website for
Jubaiha Medical Clinics — a 24-hour emergency & walk-in clinic in Al-Jubeiha, Amman.
Includes a one-tap **WhatsApp appointment booking** button.

## ✨ Features

- **Bilingual with instant AR ⇄ EN toggle** — full RTL/LTR support, remembers the visitor's choice.
- **WhatsApp booking** — every "Book" button opens WhatsApp with a ready-made message in the visitor's language, sent to **+962 7 9576 2673**.
- **Modern responsive design** — hero, medical departments, about, booking CTA, contact + map, footer, and a floating WhatsApp button.
- **Fast & dependency-free** — a single `index.html` (inline CSS/JS) plus the logo. No build step.
- **SEO & social ready** — meta description, Open Graph tags, and favicon.

## 📁 Structure

```
index.html                → the whole website
assets/logo.jpg           → clinic logo
.github/workflows/deploy.yml → auto-deploys to GitHub Pages
```

## 🚀 Free hosting — GitHub Pages (recommended)

The repo already includes an auto-deploy workflow. To go live for free:

1. Merge this branch into **`main`**.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **GitHub Actions**.
4. Done — every push to `main` publishes automatically. Your site will be at:
   `https://<your-username>.github.io/jubeiha-clinic/`

> You can also connect a custom domain later under **Settings → Pages → Custom domain**.

### Alternative free hosts (drag-and-drop, no GitHub needed)

- **Netlify Drop** — go to <https://app.netlify.com/drop> and drag the project folder in.
- **Cloudflare Pages** or **Vercel** — connect the repo and deploy with default settings.

## ✏️ Updating clinic info

All content lives in `index.html`:

- **WhatsApp number** — edit `var WA_NUMBER = "962795762673";` in the `<script>` at the bottom.
- **Pre-filled booking message** — edit the `MSG` object (Arabic + English) in the same script.
- **Phone / email / Instagram / address** — search the Contact and Footer sections.
- **Departments & text** — each language has `.ar` / `.en` spans; edit both to keep the two languages in sync.

## 📞 Clinic details

| | |
|---|---|
| Phone / WhatsApp | +962 7 9576 2673 |
| Email | bkh08706@gmail.com |
| Instagram | [@clinics_emergency](https://www.instagram.com/clinics_emergency) |
| Address | Yajoz Rd, Al-Jubeiha, Amman 11941, Jordan |
| Hours | Open 24 hours, every day |
