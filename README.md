# Sri Balaji Fancy Store — PWA package

## GitHub Pages లో పెట్టడం (deploy)

1. github.com లో కొత్త repository create చేయండి (public).
2. ఈ zip లో ఉన్న 4 items (`index.html`, `manifest.json`, `sw.js`, `icons/` folder) ని repo root లోకి upload చేయండి.
3. Repo లో: Settings → Pages → Source → "Deploy from a branch" → Branch: `main`, folder: `/ (root)` → Save.
4. 1-2 నిమిషాల తర్వాత మీకు ఒక లింక్ వస్తుంది: `https://<your-username>.github.io/<repo-name>/`

## Android లో install చేసుకోవడం

1. ఆ లింక్‌ని ఫోన్‌లో Chrome లో తెరవండి.
2. Chrome మెనూ (⋮) → "Add to Home screen" / "Install app" నొక్కండి.
3. ఇప్పుడు ఇది ఒక సాధారణ app icon లాగా Home screen మీద కనిపిస్తుంది.
4. ఒక్కసారి తెరిచాక, internet లేకపోయినా ఇది తెరుచుకుంటుంది (offline పనిచేస్తుంది) — service worker దానంతటదే files ని cache చేస్తుంది.

## గమనిక

- Internet లేకుండా data (bills, products) save కావడానికి, ఈ PWA browser యొక్క local storage వాడుతుంది — అది ఆ ఫోన్/browser లోనే ఉంటుంది.
- Bluetooth thermal printer గురించి — యాప్ లోపలే "Printer settings" స్క్రీన్‌లో steps ఉన్నాయి (RawBT app వాడాలి).
