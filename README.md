# QuotePilot iPhone PWA — deploy without a Mac

1. Download QuotePilot-PWA.zip on iPhone and unzip it in Files.
2. In Safari, create/sign in to a GitHub account at https://github.com.
3. Create a PUBLIC repository named `quotepilot-app`.
4. In that repository choose Add file → Upload files. If needed, use Safari's Request Desktop Website.
5. Upload the six files INSIDE the unzipped folder to the repository ROOT (not the ZIP itself): index.html, manifest.webmanifest, sw.js, icon-180.png, icon-192.png, icon-512.png. Commit changes.
6. Repository Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save.
7. Once published, open the HTTPS URL shown in Pages settings (usually https://YOUR-USERNAME.github.io/quotepilot-app/) in Safari.
8. Safari Share → Add to Home Screen → Add. Open the installed icon.

Features: customers, estimates, line items, taxes, statuses, print/save PDF via iOS print, JSON backup/restore, and offline app shell after first online load.

IMPORTANT: Data is saved ONLY in this device's app/browser local storage, not on GitHub. Home Screen and Safari may have separate storage. Use the installed app consistently. Export JSON backups regularly, especially before uninstalling, clearing website data or switching phones. No cloud sync, logins, payments, AI voice entry, or direct email delivery yet. GitHub Pages hosts public source code; customer data is not uploaded by this app. Review quotes before sending.
