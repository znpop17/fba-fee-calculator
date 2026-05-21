# FBA Fee Calculator

Single-page static tool for estimating US Amazon FBA fee scenarios.

## Use

Open `index.html` in a browser, download the CSV template, fill product dimensions and weight, then run the calculation.

## Input Notes

- `is_apparel` is the field used for apparel vs non-apparel fee logic.
- `category` is optional and only used for display.
- `sale_price_usd` may be blank. When blank, the page enumerates both low-price and non-low-price policy branches.

## Current Policy Scope

- Marketplace: US
- Policy version: 2026-05-07
- Includes the 3.5% US fuel and logistics-related surcharge effective 2026-04-17.
