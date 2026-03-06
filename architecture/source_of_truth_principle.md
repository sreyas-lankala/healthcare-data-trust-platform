# Source of Truth Principle

The Healthcare Data Trust Platform treats the raw data lake layer
as the authoritative source of truth.

Raw datasets are stored in their original format and are never modified.

All transformations occur in downstream layers such as staging
and curated datasets.

This design ensures reproducibility, auditability, and reliable
reprocessing of data pipelines.