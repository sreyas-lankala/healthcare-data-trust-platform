# Data Lake Layer Architecture

The Healthcare Data Trust Platform implements a layered data lake architecture.

Layers include:

raw/
  Stores original clinical datasets.

staging/
  Contains standardized datasets used for transformations.

curated/
  Contains business-ready datasets modeled for analytics.

analytics/
  Stores aggregated datasets used by dashboards and reporting tools.

This layered design improves pipeline reliability and enables clear
separation between raw ingestion and analytics workloads.