# Prototype retirement income calculator

An interactive calculator that projects KiwiSaver balances and retirement income (KiwiSaver plus NZ Super) for individuals and couples under different policy settings.

Owned by Te Ara Ahunga Ora Retirement Commission.

**Status:** Prototype. Results are illustrative and may change as the model is developed. This is not financial advice.

## Live tool

https://retirement-commission.github.io/retirement-income-calculator/

The tool is hosted on GitHub Pages directly from this repository (branch `main`, root folder).

## Privacy

All calculations run in the user's own web browser. The details a user enters (such as date of birth, income and KiwiSaver balance) are not sent to or stored by the Retirement Commission or anyone else.

## Files

| File | Purpose |
|---|---|
| `index.html` | The live calculator. This is the only file the web tool uses. |
| `Retirement Income Calculator.R` | An R Shiny version of the same calculator. Not used by the live tool. |
| `260702 NZAE Paper.pdf` | Conference paper (NZAE, June 2026) drawing on this modelling. |
| `KiwiSaver calculator review - Notes 3 July 2026.docx` | Review notes from testing in July 2026. |

## How to update the live tool

1. Edit `index.html` in this repository and commit the change to the `main` branch.
2. GitHub Pages republishes automatically, usually within a few minutes.
3. Check the live tool afterwards.

Every commit to `main` goes live, so test changes before committing. If the calculation logic changes, check whether the R version should also be updated so the two stay consistent.

## Ownership and history

- Business owner: Te Ara Ahunga Ora Retirement Commission
- Technical owner: Te Ara Ahunga Ora Retirement Commission
- Originally developed by Patrick Nolan.
## Contact

office@retirement.govt.nz
