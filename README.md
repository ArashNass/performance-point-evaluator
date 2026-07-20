# Performance Point Evaluator

An interactive, single-page seismic assessment tool that evaluates the intersection of structural capacity and earthquake demand in acceleration-displacement response spectrum (ADRS) format.

## Features

- N2 capacity-spectrum screening workflow
- Eurocode 8 and ASCE 7 demand spectra
- Embedded earthquake records and uploaded time-history support
- Uploaded response-spectrum and pushover-curve support
- Equivalent SDOF transformation and equal-energy bilinear idealisation
- Performance-point, ductility, effective-period, and roof-displacement results
- ASCE 41, EN 1998-3, Hazus, and custom drift-proxy thresholds
- Downloadable SVG charts, CSV templates, and reproducible case links
- Fully client-side calculation with no build step

## Usage

Open `index.html` in a modern browser, or use the deployed version at [arashnassirpour.com/performance-point-evaluator/](https://arashnassirpour.com/performance-point-evaluator/).

Select a demand source, provide or upload a pushover curve, configure the performance thresholds, and choose **Evaluate performance point**.

## Disclaimer

This is an educational screening tool, not a substitute for a project-specific nonlinear analysis, code assessment, or engineering judgment. Global roof drift is used only as a screening proxy; acceptance criteria are generally component- and system-specific.

## License

Licensed under the GNU Affero General Public License v3.0 only (`AGPL-3.0-only`). See `LICENSE`.
