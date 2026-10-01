SHIV TEXTILES BILLING APP V6

Files to upload to the ROOT of your GitHub repository:
- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png
- README.txt

Features:
- Billing, saved bill history, customer directory and opening balances
- Product list with editable rates and stock fields
- Samaan Nikalo / Picking List linked to saved bills
- Per-item tick marks and partial quantity tracking
- Picking progress and remaining pieces saved on this device
- Search picking lists by bill number or customer name
- Print a separate picking slip
- Export/import local backup
- Offline PWA support and modern blue-white startup intro

Important:
- Data is stored in this browser/device. Export backups regularly.
- Upload the files above directly to the repository root, not inside an extra folder.
- Enable GitHub Pages from Settings > Pages > Deploy from a branch > main > /(root).
- After updates, if an old version still appears, close the app and refresh; the service worker cache has been versioned.
