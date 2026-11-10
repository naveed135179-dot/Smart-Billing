# Ledgerly — Smart Billing

A responsive, original billing and small-business management starter app. It is built as a dependency-free static web app so it runs immediately in GitHub Codespaces.

## Run in Codespaces

Open `index.html` in the Codespaces preview, or start a simple local server from the terminal:

```bash
python3 -m http.server 8000
```

Then use **Ports → 8000 → Open in Browser**.

## Included

- Overview dashboard with sales, pending invoices, contacts, and low-stock summaries
- Invoice and estimate records with configurable default tax calculation
- Product/service catalog and stock levels
- Customer and supplier directories
- Purchase and expense records
- Sales and inventory reports, plus invoice CSV export
- Five interior-inspired palettes: Studio Sage, Terracotta Loft, Coastal Calm, Mid-century Oak, and Modern Minimal
- Browser-local persistence, JSON backup, and restore
- Responsive layout for desktop and mobile

## Data note

Records are stored in the browser's `localStorage` on the current device and browser. This starter is not a multi-user/cloud accounting system. Export backups regularly, and confirm local tax/GST requirements before using documents for business.
