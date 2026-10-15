# Vining Family Christmas

The 2026 family Christmas list is a static microsite for `https://christmas.tjvining.com/`. Open `index.html` directly for local development; no build step or package installation is required.

- Family password: `holly`
- The selected person, theme, onboarding state, and a resilient data cache are remembered locally on each device.
- Lists, claims, comments, feature requests, votes, chat, and presence synchronize through Firebase Realtime Database under the isolated `viningFamilyChristmas/2026` namespace.
- Shared mutations use transactions to reduce collisions when multiple family members make changes simultaneously.
- Item pages use Microlink for best-effort Open Graph preview images. If a retailer blocks previews, the shopping link and fallback artwork remain available.
- Every person begins with the same labeled Tru-Tone example item and can delete it after learning the list controls.

See `DEPLOY.md` for the GitHub Pages, custom-domain, Firebase rules, privacy, and launch checklist.
