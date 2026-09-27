# F1 Race Forecasts

Prospective Formula 1 forecasts by Jad, using a frozen historical modeling
pipeline. This independent portfolio project is not affiliated with Formula 1,
the FIA, or any team.

## Release status

**No genuine prospective forecast has been published yet.** Repository creation
and this README are not evidence of predictive performance. Historical replay
will never be presented here as a prospective prediction.

The first release is gated on reviewed event-specific entries, qualifying,
official confirmed grid, amendments, withdrawals and eligibility information.
Missing grid information is not evidence that a driver is ineligible.

## Frozen methodology

- Historical training: 2014-2022; validation: 2023; final test: 2024-2025.
- Preprocessing, models, calibration and race-level reconciliation were selected
  before the final test. Those test results are not used to choose a new champion.
- Confirmed-grid forecasts expose every predetermined named pipeline and the
  starting-grid and recent-form baselines, not just a favorable result.
- Outputs include predicted finishing order and each eligible driver's winner,
  podium and points-finish probabilities, with consistency diagnostics.
- Pre-weekend evidence capture is not a forecast from these grid-dependent models.
- No model refitting, weather features or simulation is introduced for this release.

## Audit trail

Each forecast release must identify its race, cutoff and generation times,
private archive and prediction hashes, model/schema/code versions, source links
and hashes, and limitations. Its complete private archive preserves exact inputs
and source observations for reproducibility.

Publication must finish before the verified race start. A server-generated
publication receipt and a downloaded-byte hash check are required; a Git author
date alone is not an independent timestamp. Corrections require a new, explicitly
linked version. Original forecasts are not overwritten. Reviewed outcomes and
subsequent scoring belong in separate, post-race records.

## Data and rights

This repository is limited to our own forecast outputs, explanatory text, source
links and hashes. It does not distribute raw FIA/F1 documents, extracted source
tables, feature matrices, historical datasets or model binaries. No logos are used.

Sources include [F1DB](https://github.com/f1db/f1db) (CC BY 4.0),
[Jolpica](https://github.com/jolpica/jolpica-f1) (data terms: CC BY-NC-SA 4.0),
[FIA](https://www.fia.com/) and [Formula 1](https://www.formula1.com/).
Additional source-specific restrictions may apply. Access to a source is not
permission to redistribute it. This repository grants no license to third-party data.

## Limitations

These are experimental forecasts, not guarantees or betting advice. Regulation,
team, driver and circuit changes can reduce transfer from historical data.
Probability constraints do not eliminate uncertainty or disagreement between
ranking and classification models. Prospective performance remains unmeasured.
