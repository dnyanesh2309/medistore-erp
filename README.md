# MediStore ERP

A self-contained browser prototype for local medical-store operations. It follows the project synopsis: medicine catalogue, batch and expiry tracking, suppliers, purchase receiving, billing with stock deduction, alerts, reports, and demo role management.

The sample catalogue contains 30 example products across common categories, including pain relief, cold and flu, allergy, gastro, diabetes, cardiac, supplements, antiseptic, eye care, and topical products. Names and batch details are demonstration data; replace them with verified store records before real use.

## Open it

Open `index.html` in a current desktop browser. No install or server is required. The interface uses Google Fonts when an internet connection is available and falls back to system fonts otherwise.

## Explore the demo

- **New sale:** type a brand name, generic name, or medicine ID. Select a suggestion to add the medicine. Completing the sale deducts stock from the earliest-expiring batch first.
- **Inventory:** search products, filter stock status, add or edit medicine details, and inspect the next batch expiry.
- **Purchases:** record supplier, medicine, batch, quantity, cost, and expiry. Receiving a purchase updates inventory.
- **Suppliers:** add supplier contacts and view outstanding balances.
- **Reports:** view sales, purchase, stock, supplier, and low-stock summaries; export inventory to CSV.
- **Team & access:** add demo users and change their role. Click the profile at the lower left to preview the role selector.
- **Alerts:** the bell shows low-stock and near-expiry items. Press **F2** to open a new sale.

## Data and scope

Changes are saved in this browser using `localStorage`. They stay on this device and browser profile; use the same browser to see them again. Reset the demo by clearing this site's local storage. This is a front-end prototype, not a production ERP: it has no server database, real authentication, multi-user synchronization, tax configuration, or regulated dispensing workflow. Do not use it to store real customer or patient data.
