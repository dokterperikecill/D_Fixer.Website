# D’Fixer

D’Fixer is a bilingual business website built for a repair and improvement company concept. The visual identity uses forest green, warm cream, amber, and charcoal, with the tagline: FIX. IMPROVE. CREATE.

## Features
- Responsive landing page
- Indonesian and English content toggle
- Service overview for repair, improvement, custom work, and installation
- Contact section with email/WhatsApp hooks
- Simple static structure suitable for GitHub Pages

## Project structure
- `index.html` — page structure
- `styles.css` — visual styling and responsive layout
- `script.js` — language switcher and contact form behavior

## How to run locally
```bash
cd /workspaces/D_Fixer.Website
python3 -m http.server 8000
```
Then open:
- http://localhost:8000

## Publish on GitHub
1. Create a new public repository on GitHub.
2. Upload these files to the repository root.
3. In the repository settings, enable GitHub Pages.
4. Publish from the main branch root folder.
5. Use a custom domain later when available.

## Contact details
The website currently uses placeholders for business contact values in `script.js`.
Update these before going live:
- `contactEmail`
- `whatsAppNumber`

## Notes
- Domain is not assigned yet, so the site is ready to deploy without a custom domain.
- The site is designed as a static marketing page and can be adapted easily for a real business.
