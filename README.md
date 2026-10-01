# khalidmill.iq — Khalid Flour Mill

Static site (HTML + CSS, no build step). Arabic RTL, mobile-first.

## Deploy (Hostinger)
hPanel → Websites → khalidmill.iq → Advanced → Git → connect repo, branch `main`, path `public_html` → enable Auto Deployment.

## Font — Thmanyah Sans
CSS family "KM Sans" loads Thmanyah via `local()` only (works on devices where it's installed), falling back to IBM Plex Sans Arabic.
Thmanyah licence FAQ allows website use but forbids uploading/hosting the font files. Get written confirmation from Thmanyah (live chat) before adding woff2 files to assets/fonts and `url()` sources to @font-face.

## Before launch
- Confirm products / grades / packaging (#products)
- Official name: معمل طحين خالد vs الخالد
- Exact Google Maps pin
- Stock images: keep licence proof (Freepik/etc.)
