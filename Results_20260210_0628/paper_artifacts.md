# Scientific Network Analysis - Artifacts Report
**Run ID:** 20260210_0628
**Date:** 2026-02-10 08:16

## 1. Quantitative Evidence Tables
| Artifact | Description |
|----------|-------------|
| `tables/global_metrics.csv` | Main network metrics including centrality and modularity. |
| `tables/confidence_intervals.csv` | Bootstrap 95% CI for modularity. |
| `tables/seed_robustness.csv` | Raw stability scores across 10 perturbed seeds. |
| `tables/calibration_distance.csv` | Z-score distances from fictional reference networks. |
| `tables/failure_modes.csv` | Automated flags for hub inflation and instability. |
| `tables/validation_pipeline.csv` | Final Pass/Fail validation summary. |

## 2. Visual Evidence
| Artifact | Description |
|----------|-------------|
| `plots/fig_hub_stability_boxplot.png` | Boxplot showing stability variance across seeds. |
| `plots/fig_loglog_ccdf_*.png` | Degree distributions proving scale-free properties. |

## 3. Audit & Data Provenance
| Artifact | Description |
|----------|-------------|
| `audit/ner_audit_sample.csv` | Random 200 tweets/entities for manual accuracy check. |
| `tables/tweet_dedup_report.csv` | Data cleaning and deduplication stats. |

*Generated automatically by Research Pipeline V2.0*
