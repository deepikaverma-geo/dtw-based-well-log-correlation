# Well Log Correlation Using Dynamic Time Warping

This repository implements well log correlation using the Dynamic Time
Warping (DTW) algorithm with the Sakoe–Chiba constraint to handle
depth mismatches and missing intervals.

The study focuses on correlating logs from two wells (J4ST2 and J6A)
and validating the results using geological interpretation.

## Methodology
- Preprocessing and normalization of well logs
- Dynamic Time Warping for depth alignment
- Application of Sakoe–Chiba band to constrain unrealistic warping
- Geological validation of correlated intervals

## Data
- Two wells: J4ST2 and J6A
- Input logs include depth-dependent petrophysical measurements

## Outcome
The DTW-based correlation improves alignment of stratigraphic units
across wells and provides a robust framework for handling missing or
non-uniform sampling in well logs.
