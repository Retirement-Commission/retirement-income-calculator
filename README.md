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

## Disclaimers and reuse

**Not official advice or a policy position.** This calculator is a general information tool developed by Te Ara Ahunga Ora Retirement Commission. It lets you explore how different settings and inputs, such as contribution rates, contribution breaks, investment returns and KiwiSaver policy settings, could affect an individual's KiwiSaver balance and retirement income. It is not personalised financial advice: it does not take into account anyone's full financial situation or goals, and it is not a recommendation to take any particular action. You may want to talk to a financial adviser about your own situation. Its outputs do not represent a Te Ara Ahunga Ora policy position.

**No warranty or liability.** The calculator is provided as-is and for general information only. Despite reasonable measures taken to ensure quality and accuracy, Te Ara Ahunga Ora makes no warranty or guarantee, express or implied, and accepts no legal liability or responsibility for the accuracy, correctness or completeness of the calculator or its results, or for any use made of them.

**Not official statistics.** Results are illustrative estimates based on the inputs entered and the assumptions used (including investment returns, inflation and NZ Super settings as at the model date). They are not official statistics or forecasts, and actual outcomes will differ.

**Reuse.** You may use, modify and adapt this code for your own work, provided Te Ara Ahunga Ora Retirement Commission is acknowledged as the source. While all care has been taken in developing this code, Te Ara Ahunga Ora gives no warranty that it is error-free and will not be liable for any loss or damage suffered as a result of its use, either directly or indirectly.

**Feedback welcome.** We welcome suggestions, feedback and corrections. Please contact office@retirement.govt.nz.

## Contact

office@retirement.govt.nz
