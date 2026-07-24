# irwinlawmn.com v2 — "Phantom Flash style"

Pure static site, GitHub Pages-ready (no build step). Built 2026-07-18.

## Pages
- index.html — home: two doors (Divorce / Crypto), Court of Appeals section
- divorce.html — family law, Rice County / southern MN, pricing-forward ($405/hr)
- crypto.html — referring-attorney audience, $2,500 Unchained Report, phantomflash.com links
- about.html — Dan bio + Court of Appeals section
- contact.html — address / phone / mailto + Formspree placeholder form

## Open TODOs (search "TODO" in the HTML)
1. **Formspree**: contact.html form action is `https://formspree.io/f/PLACEHOLDER` — create a form at formspree.io and swap the ID. Mailto fallback works meanwhile.
2. **COA audio**: Mohr v. Mohr, A26-0145 (argued 2026-07-09). mncourts.gov is behind a Cloudflare bot-check; direct MP3 could not be fetched programmatically. Find it manually at https://mncourts.gov/courtofappeals/oral-arguments (search "Mohr" / "0145"), then uncomment the <audio> tag in index.html + about.html and drop in the URL.
3. Confirm publishing the $405/hr rate on divorce.html is wanted (Dan asked for pricing-forward; rate from firm records).

Analytics: gtag G-2Y537P3ZWD on every page.
