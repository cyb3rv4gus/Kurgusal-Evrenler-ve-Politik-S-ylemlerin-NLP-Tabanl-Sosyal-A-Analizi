# Academic Network Analysis Report
**Run ID:** 20260207_2121
**Date:** 2026-02-07 21:29

## 1. Data Provenance & Cleaning
- **Deduplication:** See `tables/tweet_dedup_report.csv` for removed duplicates.
- **Entity Normalization:** See `tables/entity_norm_report_*.csv` for mapping.
- **Audit:** Random samples available in `audit/` folder.

## 2. Network Robustness & Stability
- **Metric Stability:** See `tables/metric_stability_contrast.csv` (includes 95% CI).
- **Validation Pipeline:** See `tables/validation_pipeline.csv` for Pass/Fail flags.
- **Visuals:** Degree CCDF plots available in `plots/`.

## 3. Calibration (Real vs Fictional)
- **Reference Stats:** Derived from Marvel/StarWars (`tables/calibration_reference.csv`).
- **Distances:** Real networks compared to reference (`tables/calibration_distance.csv`).

## 4. Artifacts List
- `audit/ner_audit_sample_AU_Election.csv`
- `audit/ner_audit_sample_US_Election.csv`
- `plots/fig_ccdf_degree_AU_Election.png`
- `plots/fig_ccdf_degree_Marvel.png`
- `plots/fig_ccdf_degree_StarWars.png`
- `plots/fig_modularity_stability.png`
- `tables/calibration_distance.csv`
- `tables/calibration_reference.csv`
- `tables/data_provenance.csv`
- `tables/metric_stability_contrast.csv`
- `tables/tweet_dedup_report.csv`
- `tables/validation_pipeline.csv`
