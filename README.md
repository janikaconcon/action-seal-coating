# Action Seal Coating LLC — Website

Marketing website for **Action Seal Coating LLC**, an asphalt paving and seal coating
contractor based in Sebring, Florida.

## Business details

| | |
|---|---|
| **Business** | Action Seal Coating LLC |
| **Address** | 301 Ruffians Way, Sebring, FL 33875 |
| **Phone** | (863) 451-6591 |
| **Hours** | 8:00 AM – 9:00 PM, seven days a week |
| **Rating** | 5.0 ★ from 10 Google reviews |
| **Service area** | Sebring and surrounding Highlands County |

## Services

- Asphalt paving
- Seal coating
- Commercial parking lots
- Crack filling & repair
- Excavation & grading
- Resurfacing & overlay

## Running locally

The site is fully static — no build step, no dependencies.

```bash
# from the repo root
python3 -m http.server 8000
# then open http://localhost:8000
```

Or simply open `index.html` in a browser.

## Structure

```
index.html      Single page — all CSS and JS are inline
images/         8 photographs of paving and seal coating work
```

## Deploying

Because everything is static and `index.html` sits at the repo root, the site can be
served directly by **GitHub Pages** (Settings → Pages → Deploy from branch → `main` / root).

## Notes

- The estimate forms have no backend. They validate the visitor's name and phone, then
  build a pre-filled text message and a tap-to-call link, so a request actually reaches
  the business instead of showing a fake "message sent" confirmation.
- Photographs are professional stock imagery of paving and seal coating work, not the
  company's own job photos. Replace them with real project shots when available.
