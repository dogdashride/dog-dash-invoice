# Dog Dash Invoice Web App

Separate GitHub Pages app for manually importing Dog Dash booking requests from WhatsApp and creating invoice recaps. This does not modify the existing booking form.

## Publish on GitHub Pages
1. Create a new repository, for example `dog-dash-invoice` (keep the booking repository unchanged).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages** and select the `main` branch and `/ (root)` as the publishing source (or use the repository's existing Pages deployment method).
4. Wait for the Pages deployment, then open the published URL.

## Included
- Manual WhatsApp booking-message import
- Dog Taxi fare calculation matching the booking form: up to 5 km Rp65,000; over 5–15 km Rp90,000; over 15–20 km Rp110,000; over 20 km +Rp10,000 per additional km
- Round-trip taxi fare doubles the route fare; extra passenger Rp30,000 each; additional dog Rp20,000 each
- Editable rates, discounts, automatic totals, print/save as PDF, WhatsApp summary, invoice history, saved customers, CSV export, JSON backup and restore
- Mobile-friendly English interface and embedded Dog Dash logo

## Important storage note
Invoices, customers and rates are saved in browser local storage on the device/browser where you use the app. They do not automatically sync across devices or browsers. Use **Export backup** regularly and keep the JSON file somewhere safe.

## Manual review required
Dog Walking, Dog Cafe / Trip and Other requests may need a manual quote. The importer marks these as quote-required rather than pretending the booking form provided a final price. Always verify the route, price, discounts and details before saving or sending an invoice.
