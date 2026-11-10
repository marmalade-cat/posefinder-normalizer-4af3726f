PoseFinder-and-Normalizer

A tiny single-file prototype demonstrating dataset ingestion and normalization for pose/time-series data. Open index.html in a browser, paste or drop CSV/JSON files (ZIP not executed in this demo), and click "Analyze". The app will detect columns that look like time, x/y/z or orientation fields and produce a normalized CSV/JSON preview plus a short report.

Limitations: This prototype does not perform network crawling. ZIP handling is stubbed (UI accepts .zip but does not extract). Intended as a clear, runnable example of normalization logic without external dependencies.