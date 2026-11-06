TRUNK STOCK INVENTORY APP

WHAT IT DOES
- Mobile-friendly inventory with + and - controls
- Updates the date/time whenever quantity changes
- “Use + note” subtracts one item and saves a usage note
- Stores data locally on the device
- Exports/imports JSON backups
- Works offline after installation

INSTALL ON A HOME SCREEN
This app must be served from an HTTPS website for reliable installation and offline use.
1. Upload the contents of this folder to an approved internal web host, SharePoint-supported static host, GitHub Pages, Netlify, or Cloudflare Pages, consistent with your company policy.
2. Open the HTTPS address on your phone.
3. iPhone/iPad: Safari > Share > Add to Home Screen.
4. Android: Chrome > menu > Install app or Add to Home screen.

IMPORTANT
Inventory and notes remain on the individual phone/browser. They do not sync across devices. Export a backup regularly. Do not enter patient-identifiable information in notes. For shared multi-device inventory, connect the interface to an approved data source such as Microsoft Lists or Dataverse.

UPGRADE V2
- Add, edit, and delete device records from the app.
- Uses the SAME localStorage key (trunkStockV1), so replacing the website files does not reset existing quantities, timestamps, or usage notes on the same device/browser profile.
- IMPORTANT: Export a backup before upgrading. Deleting a device also deletes its local notes.

UPGRADE V3
- Delete individual usage notes from note history.
- Zero-quantity products are prominently marked OUT OF STOCK with a red highlight.
- Visual theme updated to a Stryker-inspired black, white, and yellow palette.
- Keeps the SAME localStorage key trunkStockV1, preserving existing inventory, timestamps, and usage notes on the same device/browser profile.
- Export a backup before replacing hosted files.

V3 DARK DASHBOARD UPDATE
- Dark navy high-contrast theme.
- Dashboard with Devices, Units, Low Stock, Out of Stock.
- Dashboard Low Stock and Out of Stock cards are tappable filters.
- Low Stock defaults to quantity 1 when a device has no PAR field yet; if a PAR field exists, low stock is quantity below PAR and above zero.
- Keeps the same trunkStockV1 storage key to preserve inventory, timestamps, and notes.
