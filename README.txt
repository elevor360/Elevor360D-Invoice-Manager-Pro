Elevor360D Invoice Manager Pro V1
Original offline-first browser app. No source code from Simple Invoice Manager is included.

Upload the CONTENTS of this ZIP to the root of a public GitHub Pages repository.
Enable GitHub Pages (main branch / root), then visit the HTTPS address.
Chrome controls when a direct PWA installation prompt is offered.
For an advert, upload adverts/advert.jpg, then set enabled=true in advert.json.

IMPORTANT: Data is stored only in the current browser/device. Download backups regularly.
This is a basic single-user invoice manager, not accounting or tax-compliance software.
The VAT rate is manually entered. Verify invoice details and tax treatment before issuing.
Printing uses the browser print dialog; select Save as PDF to export.

V1.1: Updated install prompt handling, manifest icon purposes, and cache version. Direct installation is only possible when Chrome fires beforeinstallprompt.

V1.2: Gold Elevor360D logo added to header. Install button remains visible in normal browser mode and hidden in standalone installed mode.

V1.3: Installation button no longer incorrectly treats standalone display mode as proof of installation. App-style windows show instructions for opening the URL in normal Chrome. Navigation and app script use network-first caching for faster updates.

V1.4: Unique Invoice Manager Pro manifest identity and cache revision. IMPORTANT: The unique manifest ID assumes GitHub repository path /Elevor360D-Invoice-Manager-Pro/. If your actual repository path differs, edit manifest.webmanifest id to match that path. Chrome may still route links into an already installed Local Deals app due to its link-handling settings; that cannot be forced from this app.

V1.5: Settings & Backup > Business details now saves a business logo, name, address, email, phone, website and payment instructions. The logo appears on printed/PDF invoices and is included in JSON backups. Upload all files to the SAME existing GitHub Pages repository to retain browser-stored records. Back up before updating.
