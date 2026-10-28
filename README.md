# Bawabet Damascus restaurant demo

Arabic, right-to-left restaurant POS demo with ordering, delivery, stock, shifts, reports, expenses and payroll screens.

## Run

Open `index.html` in a browser, or serve this directory with any static web server. No build or backend is required. Google Fonts are optional; local fallback fonts work offline.

This is an interactive demo: changes are kept in browser memory and reset on reload. Use sample data only.

## Files

- `index.html`: page and core demo logic.
- `pos-modern.css`: interface styles and responsive layouts.
- `pos-modern.js`: POS interface and interactions.
- `menu-data.js`: sample menu.
- `order-details.js`: takeaway and delivery customer details.
- `finance-demo.js`: expenses and payroll.
- `Bawabet-Damascus-Demo.html`: standalone offline edition.

## Validation

Run `node finance-demo.test.cjs` for finance checks. POS and delivery layouts were checked in Edge at widths of 320, 390, 720, 768, 1024, 1366 and 1440 pixels. Narrow invoice layouts keep quantities, totals and removal controls visible; the unit price is shown separately on larger screens. Tables scroll within their own containers.

## GitHub Pages

Publish the `main` branch from the repository root using GitHub Pages (Settings → Pages → Deploy from a branch).
