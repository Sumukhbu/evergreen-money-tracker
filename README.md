# Evergreen — Money Tracker

An installable, forest-green-and-cream personal finance Progressive Web App.

## Publish and install on Android
1. Create a GitHub repository (public if using free GitHub Pages).
2. Upload `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, and `icon-512.png` to the repository root.
3. In repository Settings → Pages, publish from the `main` branch and root folder.
4. Open the resulting HTTPS site in Chrome on Android.
5. Use Chrome menu → Install app or Add to Home screen.

## Features
- Home dashboard, funds, insights, transaction history, settings.
- Seven starting funds, all with zero balances.
- Add, edit, and delete funds.
- Record salary with actual date and time; expected payday is the last calendar day of each month.
- Timestamped transaction records; edit/delete entries and reverse their effect on balances.
- Record savings contributions, withdrawals, purchases, monthly spending and fixed RD/fuel payments.
- Planned allocation pie chart, six-month expense trend, category spending bars.
- IndexedDB storage with localStorage fallback, offline caching and manual JSON backup/restore.
- CSV transaction export and persistent-storage request.
- Monthly budgets and savings targets.

## Initial plan
Income ₹25,000; RD ₹10,000; fuel ₹3,000. Funds: Emergency Fund 1 ₹3,000, Emergency Fund 2 ₹1,500, Food ₹3,000, Clothes ₹1,500, Shoes ₹1,500, Perfume ₹750, Gifts ₹750. All savings balances start at ₹0. Tracker start date 11 October 2026; expected payday is the last day of each month.

## Privacy
No bank integration and no automatic cloud sync. Data is stored locally in the browser on this device. Export backups regularly; browser storage can still be cleared or lost. Do not put real transaction data into a public source repository. Only the app code should be uploaded to GitHub Pages.
