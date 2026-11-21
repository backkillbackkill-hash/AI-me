# Forex Chart AI

เวบ AI វិភាគឆាត Forex (PWA) — ដាក់រូប screenshot ឆាត រួច AI ប្រាប់ BUY/SELL, Entry, SL, TP, ចលនាខ្លាំង, ការហាមចូល។
Upload a chart screenshot and get BUY/SELL, entry, SL/TP, strong-move scenarios and no-trade warnings.

## Deploy on GitHub Pages
1. Create a new repo, upload all files (index.html, manifest.webmanifest, sw.js, 4 png icons, .nojekyll).
2. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save.
3. Open `https://<username>.github.io/<repo>/` on your phone.
   - iPhone Safari: Share → Add to Home Screen
   - Android Chrome: menu → Install app
4. Paste your Anthropic API key in the page (saved only in your browser's localStorage).

## Notes
- Never commit your API key to the repo.
- Dollar figures assume 1 lot = $10 per pip; cent/micro accounts (e.g. EURUSDm) differ.
- Not financial advice. Test on a demo account.
