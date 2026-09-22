# grimshell-legal

Public-facing legal and support pages for **Grimshell**, the iOS, iPadOS and
macOS app.

Live at <https://magnusjune.github.io/grimshell-legal/> via GitHub Pages, served
from `main`. Editing a file and pushing updates the live page; there is no build
step.

- `index.html` — privacy policy. This is the URL App Store Connect wants.
- `support.html` — support page. This is the Support URL.
- `style.css` — shared styling, Grimshell's palette, light and dark.

The privacy policy describes what the app actually does — no accounts, no
network, no analytics, no third-party SDKs, progress in the user's own iCloud
key-value store, and a terminal that is simulated rather than real. Keep it in
step with the app's `PrivacyInfo.xcprivacy` and the App Privacy answers in App
Store Connect; if those three disagree, App Review will notice.

This repository is public by design. It holds published text only — no source,
no identifiers, no configuration.
