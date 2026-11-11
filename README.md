# Nishika Stock

Wholesale + retail **ladies suits & textiles** ke liye offline PWA — stock, location (kahan rakha hai), purchase, billing, udhaar, reports. Koi server nahi; data phone ke andar (IndexedDB) save hota hai.

## Features
- **Stock**: item code, naam, category, fabric, colour, size, unit (Set/Piece/Bundle/Meter), purchase/wholesale/retail rate, low-stock alert
- **Kahan rakha hai**: har item ka Rack/Godown location, location-wise view aur search (code/naam/colour/rack)
- **Purchase (maal aaya)**: supplier, bill no, rate, location, partial payment
- **Sales / Billing**: Retail & Wholesale, discount, optional GST, udhaar, print/PDF, WhatsApp bill
- **Returns**: sale return / purchase return
- **Parties**: customers & suppliers, khata (ledger), payment aaya/diya, WhatsApp reminder
- **Accounts**: din ka hisaab (day book), kharcha, udhaar list
- **Reports**: sales, item-wise bikri (kitna bika), stock, location-wise, purchase, profit & loss, outstanding, low stock, slow moving — sab CSV export
- **Data**: JSON backup/restore, items CSV import/export, demo data

## GitHub Pages pe chalana
1. Repo → **Settings → Pages**
2. Source: **Deploy from a branch** → Branch: `main` → `/ (root)` → Save
3. Link: `https://<username>.github.io/nishika-stocks/`

## Phone pe install
- **iPhone**: Safari → Share → *Add to Home Screen*
- **Android**: Chrome → menu → *Install app*

## Zaroori
- Data sirf usi phone mein hota hai. **Hafte mein ek baar Backup** lo (More → Backup lo).
- Update ke baad app ko 2 baar band karke kholo (service worker refresh).

## Files
`index.html` (poori app), `manifest.json`, `sw.js` (offline), `icons/`, `fonts/`.
