# JSI Cabinetry – Safety Data Sheets (Avance Production)

Static, searchable SDS site. Open `index.html` or visit the GitHub Pages URL.

- `index.html` – the site (search + list; no build step, no dependencies)
- `sds/` – one PDF per product plus `SDS_All_Sheets_Combined.pdf` (full binder with index and page numbers)
- `sds-catalog.json` – product code, name, manufacturer, signal word, revision date for each sheet

## Updating a sheet
1. Replace the PDF in `sds/` (keep the same file name so existing links and QR codes keep working).
2. If the product name or revision date changed, edit the matching card in `index.html` (search for the product code).
3. Commit and push – GitHub Pages republishes within a minute or two.
